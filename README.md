# Neural Network-Enhanced Fault-Tolerant SRAM with Adaptive Error-Correcting Code

##  Project Overview

This project enhances the fault tolerance of an 8-bit Static Random Access Memory (SRAM) system using a hybrid approach that combines traditional error-correcting techniques with neural networks. The system utilizes Hamming Code (12,8) for single-bit error detection and correction, while a trained neural network model handles complex fault patterns. The project has been designed and tested using Logisim, Python (TensorFlow/Keras), MATLAB, and Xilinx Vivado.

##  Features

- **Hybrid Fault-Tolerance Approach**: Integrates Hamming Code and Neural Networks for enhanced error correction.
- **Neural Network-Based Error Detection**: Uses machine learning to predict and correct complex fault patterns.
- **FPGA Implementation**: Simulated and tested in Xilinx Vivado for real-world feasibility.
- **Energy Efficient Design**: Consumes only 2W of total power (1.972W dynamic, 0.028W static).
- **Dataset-Driven Learning**: Trained with error datasets to improve fault detection accuracy.

##  Tools & Technologies Used

- **Logisim**: SRAM circuit design and simulation.
- **Python (TensorFlow/Keras)**: Neural network model training and testing.
- **Xilinx Vivado**: FPGA-based hardware implementation and power analysis.
##  Performance Metrics

- **Confusion Matrix & ROC Curve**: Evaluate neural network accuracy.
- **FPGA Utilization**: Efficient resource allocation (18% area usage).
- **Power Consumption**: Optimized design with 2W total power consumption.

##  Applications

- **AI Accelerators**: Enhancing computational reliability in machine learning hardware.
- **Aerospace Systems**: Ensuring robust memory operations in high-radiation environments.
- **Healthcare Devices**: Enabling error-free data storage in life-critical applications.
- **IoT Systems**: Improving reliability in low-power smart devices.

##  Future Enhancements

- **Improve Neural Network Accuracy**: Enhance training techniques for higher precision.
- **Optimize Power Consumption**: Make it more suitable for battery-operated devices.
- **Explore Quantum Error Correction**: Investigate next-gen memory resilience techniques.
- **Hardware Acceleration**: Implement real-time neural network inference on FPGA.

