# Data Science Game 2018

## Check the documentation
- [Azure docs](https://docs.microsoft.com/en-us/azure/index)

## DSVM setup
TL;DR - just make it:
- [Create Ubuntu DSVM](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/dsvm-ubuntu-intro)
- [Create Windows DSVM](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/provision-vm)

### Learn about it
- [Overview](https://azure.microsoft.com/en-us/services/virtual-machines/data-science-virtual-machines/)
- [What's on the DSVM image?](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/dsvm-tools-overview)
- [Data Science Virtual Machine overview](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/overview)
- [Deep Learning Virtual Machine overview](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/deep-learning-dsvm-overview)

### GPU FYI

TL:DR; Use NC or NV (V1) SKU VMs for GPUs.

You all have a certain type of Azure grant (Academic Grant - 143P) which doesn't have immediate access to NVS/NDS/NCSv3/NCSv2 VMs due to quota limitations.
You may create a quota request to get access to these VMs, but in general due to high demand for these graphics-enabled VM types, availability is limited for customers using free/benefit/sponsorship subscriptions.
You won't need a quota increase to use the regular VC or NV (V1) VMs, so those are the best bet for getting up and started quickly. 

## Other Azure data science/machine learning tools
- [Machine learning tools overview](https://docs.microsoft.com/en-us/azure/machine-learning/)
- [Azure machine learning service (preview)](https://docs.microsoft.com/en-us/azure/machine-learning/service/)

## Example labs
- [Keras on Azure notebooks](https://github.com/Microsoft/computerscience/blob/master/Labs/AI%20and%20Machine%20Learning/Keras/Keras.md) - from Justin's talk
- [TensorFlow on Azure Data Science Virtual Machine](https://github.com/Microsoft/computerscience/blob/master/Labs/AI%20and%20Machine%20Learning/TensorFlow/TensorFlow.md)
