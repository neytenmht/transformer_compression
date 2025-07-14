## Project Overview

This repository contains the code and written report from a master thesis on neural network model compression.

## Description

The project introduces a compression framework that identifies weight matrices suitable for low-rank approximation and applies rank truncation to reduce model size. A key aspect of the method is selecting appropriate truncation ranks automatically. The framework is applied to Transformer models and shows improved compression performance compared to standard low-rank methods. Both fine-tuned and pre-trained models are considered, with and without access to target dataset samples.

## Notes

- Datasets are not provided.
- The code was developed for Google Colab using a specific Google Drive environment and is not directly runnable after cloning this repository. It is included for reference only.

## Keywords

Transformers, Neural Network Compression, SVD, Low-Rank Approximation, Matrix Rank, Fine-Tuning
