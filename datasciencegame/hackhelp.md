# Data Science Game 2018

## Azure basics

## DSVM setup

## GPU FYI

TL:DR; Use NC or NV (V1) SKU VMs for GPUs.

You all have a certain type of Azure grant (Academic Grant - 143P) which doesn't have immediate access to NVS/NDS/NCSv3/NCSv2 VMs due to quota limitations.
You may create a quota request to get access to these VMs, but in general due to high demand for these graphics-enabled VM types, availability is limited for customers using free/benefit/sponsorship subscriptions.
You won't need a quota increase to use the regular VC or NV (V1) VMs, so those are the best bet for getting up and started quickly. 

## Example labs
[Keras on Azure notebooks](https://github.com/Microsoft/computerscience/blob/master/Labs/AI%20and%20Machine%20Learning/Keras/Keras.md) - from Justin's talk
[TensorFlow on Azure Data Science Virtual Machine](https://github.com/Microsoft/computerscience/blob/master/Labs/AI%20and%20Machine%20Learning/TensorFlow/TensorFlow.md)
