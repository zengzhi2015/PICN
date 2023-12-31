# Physics-informed ConvNet: Learning Physical Field from a Shallow Neural Network

This repository hosts the source code for the paper "Physics-informed ConvNet: Learning Physical Field from a Shallow Neural Network", aiming at the development of a novel Artificial Intelligence (AI)-based Physics-Informed Convolutional Network (PICN) for efficient physical modeling and computation with limited data. The novel AI framework enriches machine learning with physical science for accurate predictions even with few noisy measurements from an experiment.

## Table of Contents
- [Introduction](#introduction)
- [Contact](#contact)
- [Citation](#citation)

## Introduction
Abstract: We present a new approach for solving nonlinear partial differential equations (PDEs)on regular or irregular domains based on physics-informed ConyNet, which we call the PICN. The physical field is generated by a deconvolution layer and a single convolution layer. Unlike the standard Physical Information Neural Network(PINN) approach, the convolutions corresponding to the finite-difference filters are used to estimate the spatial gradients forming the physical operator. The total loss function involving boundary conditions and the physical constraints in irregular geometry domains is calculated using an efficient linear interpolation network. The theoretical analysis of PICN convergence is performed, and several examples for solving nonlinear PDEs with multifrequency characteristics are executed. The theory and examples confirm the effectiveness of PICN for estimating the physical field with high-frequency components. A series of numerical cases are performed to validate the proposed method, including the solving (and estimation)of nonlinear physical operator equations and recovering physical information from noisy observations. The numerical results demonstrate the higher accuracy and faster convergence performance of PICN compared with the standard PINN. This paper is adapted from the work originally posted on arXiv.com by the same authors (arXiv:2201.10967,Jan 26, 2022). The potential advantage in approximating complex physical fields with multi-frequency components indicates that PICN may become an alternative efficient neural network solver in physics-informed machine learning.

## Contact
For any queries, feel free to reach out to us at:
* P. Shi - shipengpeng@xjtu.edu.cn
* Z. Zeng - zhizeng@mail.xidian.edu.cn
* T. Liang - liangtianshou@gmail.com

## Citation
If you find our work useful in your research, please consider citing our paper:
[Shi, Pengpeng, Zhi Zeng, and Tianshou Liang. "Physics-informed ConvNet: Learning Physical Field from a Shallow Neural Network." arXiv preprint arXiv:2201.10967 (2022).]