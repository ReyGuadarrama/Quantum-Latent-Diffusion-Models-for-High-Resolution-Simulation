# Hybrid/Quantum Latent Diffusion Models for High-Resolution Simulation

Research code developed by **Miguel Pámanes Morales** during **Google Summer of Code 2026**, with **ML4SCI / QMLHEP**.

This project investigates classical and hybrid quantum–classical generative models for quark and gluon jet images. It explores image-space diffusion, variational autoencoders, latent diffusion, and parametrized quantum circuits within the denoising process.

**[Read the full project report](https://mpm-cvr.github.io/gsoc-2026-report/)** for the methodology, results, challenges, and future work.

## Repository Structure

| Directory              | Contents                                                                             |
| ---------------------- | ------------------------------------------------------------------------------------ |
| `Classical/DIFFUSION/` | DDPM, DDIM, and Flow Matching experiments.                                           |
| `Classical/VAE/`       | VAE experiments on introductory datasets and jet images.                             |
| `Classical/LDM/`       | Classical latent diffusion models and a simplified baseline for quantum experiments. |
| `Quantum/`             | Quantum bottleneck, patchwise denoising, and hybrid spatial-mixing experiments.      |

## Current Status

The experiments demonstrate that quantum circuits can participate in latent denoising. However, the completed comparisons do not establish an overall quantum advantage, and the classical latent U-Net remains the strongest generative-quality reference.

Some later experiments described in the report are not yet included in this repository.

## Running the Experiments

Implementations are provided as Jupyter notebooks. Configure the required dependencies and dataset paths before running them. Dataset files are not included in this repository.




🚧 Note: This repository is under active development and continuously updated.
