# MM811 Programming Assignment

This repository contains Kaggle notebooks for the programming assignment, covering image classification, compact latent representations, sequence modelling, and image generation using PyTorch.

## Assignment Contents

- **Problem 1 – Image Classification:** Implements LeNet-5 to classify handwritten digits from the MNIST dataset.
- **Problems 2 & 3 – Binary Latents and Sequence Modelling:** Trains a binary variational autoencoder on MNIST and explores token-based modelling approaches, including sequence-to-token classification, a causal Transformer decoder, and sequence-to-histogram prediction.
- **Problem 4 – CIFAR-10 Autoencoders and Generation:** Trains continuous and discrete autoencoders on CIFAR-10, then uses the learned latent representations in generative modelling experiments, including diffusion and autoregressive Transformer approaches.

## Notebooks

| File | Contents |
|---|---|
| `Assignment Problem 1.ipynb` | LeNet MNIST classification |
| `Assignment Problem 2 & 3.ipynb` | Binary VAE and sequence-modelling experiments |
| `assignment-problem-4.ipynb` | Autoencoders and latent generative models experiment on CIFAR-10 dataset |

## Requirements

The notebooks use Python and libraries including **PyTorch**, **NumPy**, **Matplotlib**, and **scikit-learn**. Additional dependencies are installed or imported in the relevant notebooks.

## How to Run

1. Open the notebooks in Kaggle.
2. Make sure the required MNIST or CIFAR-10 dataset is available. 
3. Install any missing dependencies.
4. Run the notebook cells in order.

For the CIFAR-10 experiments, a GPU accelerator is recommended because training can be computationally intensive for more epochs.

## Outputs

The notebooks generate model checkpoints, training curves, reconstruction visualisations, generated image samples, and evaluation metrics such as accuracy, PSNR, and FID where applicable.
