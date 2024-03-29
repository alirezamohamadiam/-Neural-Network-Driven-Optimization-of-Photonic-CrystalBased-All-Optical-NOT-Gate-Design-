# Neural Network-Driven Optimization of Photonic Crystal-Based All-Optical NOT Gate Design

This project has been accepted for presentation at the prestigious Third International IEEE Conference on Distributed Computing and High-Performance Computing (DCHPC2024).

## Overview

This repository contains code and resources related to a comprehensive study on the application of neural networks to optimize design parameters for an all-optical NOT gate using photonic crystals. The research focuses on leveraging the unique properties of photonic crystals to control light flow and create small optical devices, specifically the NOT gate in this case.

## Research Objectives

The primary objectives of this study are as follows:

- Exploration of Photonic Crystals: Understand the unique properties of photonic crystals and their role in controlling light flow within optical devices.
- Neural Network Architecture: Introduce a three-layer neural network architecture designed to forecast crucial parameters necessary for the effective functioning of the NOT gate.
- Optimization of Rod Parameters: Conduct systematic simulations to optimize the radius of the rods (R0 and R1) crucial for the operation of the NOT gate.
- Evaluation of Model Accuracy: Compare the results obtained from the neural network predictions with actual outputs, emphasizing the Mean Absolute Error (MAE) for 'R0' and 'R1' to confirm the precision of the model.


## Key Findings

The research demonstrates the effectiveness of the neural network in optimizing the rod radius and predicting gate behavior. The main rationale behind utilizing neural networks is to achieve higher prediction accuracy, particularly in handling intricate scenarios involving parameters like the lattice constant and rod radius in photonic crystals.

## Results

The systematic simulations and analyses reveal outstanding accuracy, with a Mean Absolute Error of 0.003 for 'R0' and 0.006 for 'R1.' This underscores the model's capability to replicate the behavior of the NOT gate across various input configurations.

## Prerequisites

The following software and libraries are required to run this project:

- Python version: 3.10.12
- pandas version: 1.5.3
- numpy version: 1.23.5
- tensorflow version: 2.15.0
- scikit-learn version: 1.2.2

## License

MIT License

Copyright (c) 2024 Alireza Mohammadi


