Project Description

This project implements a workflow where simulation data are extracted from MATLAB/Simulink and then fed as input to Python for further processing and learning-based analysis. In practice, MATLAB is used to generate or export the required time-series signals (e.g., voltage/current and time vectors), and Python consumes these exported datasets for training, evaluation, or post-processing.

The provided code focuses on the simulation of a linear capacitor (linear capacitance model) within a photovoltaic-related dynamic modeling context. The implementation is designed to reproduce the expected transient behavior of a linear capacitor under the applied excitation, enabling consistent generation of data that can later be used for parameter estimation or model validation pipelines.

References

If you use this code or build upon it, please cite the following works:
Shamsmohammadi, N., & Spagnuolo, G. (2025, June). Photovoltaic Module Single-Diode-Model Identification by a Physics-Informed Neural Network. In 2025 International Joint Conference on Neural Networks (IJCNN) (pp. 1-8). IEEE.
