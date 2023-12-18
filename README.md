# Hardware Development Project

Hardware AI Accelerator

- A fast, low power accelerator for classification. 
- Characterize The Power Usage
- - As a function of precision
- - As a function of accuracy

Tools: 
- Tensorflow
- HLS4ML (https://fastmachinelearning.org/hls4ml/)
- Vivado 2020.1 (https://www.xilinx.com/support/download.html)

Hardware Used: 
- PYNQ Z2
- - A combined ARM/FPGA system. HLS4ML has I/O bindings for this board

## Machine Learning Model

Simple Classifier (Yes/No) 
- What are we classifying? 
- Once we figure that out, we use HLS4ML

## Translation

HLS4ML, we use VIVADO 2020.1. 

Rather simple process
- Import hls4ml package
- Convert using dedicated function
- Characterize Accuracy, etc.

Transfer to Vivado
- Build I/O skeleton
- Characterize Power Usage (simulated)
- Get it on the PYNQ-Z2 and test

## Testing Stage

Measure Accuracy/Power Usage on PYNQ z2 board