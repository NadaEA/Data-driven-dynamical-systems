# Data-driven dynamical systems

## Introduction
This repository contains the python implementation and reports of the assignments of MATH 494: Data-driven Dynamical Systems taken at Concordia University, Montreal. 

## Contents

### Assignment 1
We examine the application of Dynamic Mode Decomposition to the separation of the background and foreground of short videos. Through the use of SVD, proper low-rank truncation of high dimensional matrices and eigenvalue distribution analysis we achieve the separation of the videos into both parts and uncover in which ways changing certain variables such as the rank of truncation and the number of modes selected can affect results.

### Assignment 2
We discuss taking a data-driven approach to ”rediscover” the laws of physics underlying two simple spring-mass systems, one where no noise is present and another where some disruption of the motion is introduced, through the use of principal component analysis and sparse identification of nonlinear dynamics and examine their respective limitations. We begin by analyzing three videos each representing a coordinate system capturing the motion of a bucket of paint springing up and down to extract a number of principal components from the positional data produced by tracking the centre of the bucket frame to frame. We then use the principal components to apply the SINDy algorithm to uncover the second order ordinary differential equation representing a simple harmonic oscillator whose solution is the vertical displacement of the bucket through time.

### Assignment 3
We explore the training of a forecasting model for the Lorenz system via the use of Recurrent Neural Networks. We begin by generating the solutions of our dynamical system for various values of the variable ρ, some of which induce chaotic behaviour while others do not. We feed our generated data to a Recurrent Neural Network and optimize for performance by examining the effects of changes to the loss function and the size of the time step of the variables on the model’s ability to forecast the solutions of the Lorenz system for both known and novel values of ρ.

### Final project
We attempt the implementation of Sliding-Window Dynamic Mode Decomposition on two videos with the purpose of analyzing its performance in identifying fast and slow movement. The first video is one where dynamics are present on a single time scale while the second features dynamics present on two different time scales. Finally, we compare the performance of the method to the performance of the standard DMD algorithm.
