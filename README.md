# GPU Acceleration Benchmark: Matrix Multiplication

This project demonstrates the impact of Hardware Acceleration (GPU) on Machine Learning operations compared to standard CPU processing. 

## Overview
Matrix multiplication is the backbone of Deep Learning algorithms (e.g., in Neural Networks). This script benchmarks the performance difference between running large-scale tensor operations on a CPU versus an NVIDIA T4 GPU using **PyTorch**.

## Results
The benchmark performs a multiplication of two **10,000 x 10,000** matrices.

* **CPU Time:** ~14.5 seconds
* **GPU Time:** ~0.002 seconds
* **Speedup:** ~6000x faster (varies based on hardware)

![Benchmark Graph](result.png)
*(Note: Ensure you view the 'result_graph.png' in the file list to see the generated plot)*

## Technologies
* **Python 3.x**
* **PyTorch (CUDA enabled)**
* **NumPy** & **Matplotlib**

## How to Run
1. Open this notebook in Google Colab.
2. Change Runtime Type to **T4 GPU**.
3. Run the cells to observe the computational speedup.
