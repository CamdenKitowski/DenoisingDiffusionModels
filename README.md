# Denoising Diffusion Model for MNIST Dataset

This repository implements a simplified version of the denoising diffusion model from scratch using PyTorch with MNIST dataset.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [Notebook Overview](#NotebookOverview)
- [Results](#results)

## Introduction

The Denoising Diffusion Model is a powerful tool for generating high-fidelity images by eliminating noise from initially noisy inputs. At its core, this model harnesses the principles of diffusion processes to iteratively refine images. Within image generation tasks, noise elimination stands as a pivotal stride in crafting clear and authetic images. This model within the notebook gradually transforms a noisy input image into a clean output image. 

## Usage

1. Clone the repository

2. Launch Jupyter Notebook or Google Colab.

3. Open the `DenoisingDiffusionModel.ipynb` notebook.

4. Follow the instructions to execute the code cells.

## Notebook Overview

This notebook will walk through the following steps.

1. Dataset - Explore dataset

2. Build Diffusion Model - Implement forward process, noise scheduler, and backward process. 
    2.1 Implement forward process with a linear noise scheduler.
    2.2 Implement backward process with the U-Net model.
    2.3 Implement loss function
    2.4 Sample new images
    2.5 Train model

3. Plot and Visualize Results.

## Results

I initially trained the U-Net model using google colab, but google colab timed out. I trained the model using a Nvidia 2080 Super GPU for a couple of hours for 100 epochs. The images are small (28x28) and converged quickly. The results are at the bottom of the notebook.
