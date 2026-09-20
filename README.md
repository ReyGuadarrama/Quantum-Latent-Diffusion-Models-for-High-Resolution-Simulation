# Hybrid/Quantum Latent Diffusion Models for High-Resolution Simulation

Research code developed by **Miguel Pámanes Morales** during **Google Summer of Code 2026**, with **ML4SCI / QMLHEP**.

This project investigates classical and hybrid quantum–classical generative models for quark and gluon jet images. It explores image-space diffusion, variational autoencoders, latent diffusion, and parametrized quantum circuits within the denoising process.

**[Read the full project report](https://mpm-cvr.github.io/gsoc-2026-report/)** for the methodology, results, challenges, and future work.

## Repository Structure

| Directory              | Contents                                                                                         |
| ---------------------- | ------------------------------------------------------------------------------------------------ |
| `Classical/DIFFUSION/` | DDPM, DDIM, and Flow Matching experiments.                                                       |
| `Classical/VAE/`       | VAE experiments on introductory datasets and jet images.                                         |
| `Classical/LDM/`       | Classical latent diffusion models and a simplified baseline for quantum experiments.             |
| `Quantum/`             | Quantum bottleneck, patchwise denoising, hybrid spatial-mixing experiments and Final Experiment. |

## Current Status

The experiments demonstrate that quantum circuits can participate in latent denoising. However, the completed comparisons do not establish an overall quantum advantage, and the classical latent U-Net remains the strongest generative-quality reference.

Some later experiments described in the report are not yet included in this repository.

## Dataset

The jet-image experiments use quark and gluon data with three detector channels: **Tracker, ECAL, and HCAL**. The original **125 × 125** images are cropped to **64 × 64**, with preprocessing documented in the corresponding notebooks.

**[Access the dataset on Google Drive](https://drive.google.com/file/d/1WO2K-SfU2dntGU4Bb3IYBp9Rh7rtTYEr/view?usp=sharing)**

Dataset files are not included in this repository. Download the data and update the local dataset paths in the notebooks before running the experiments.


## Running the Experiments

Implementations are provided as Jupyter notebooks. Configure the required dependencies and dataset paths before running them. Dataset files are not included in this repository.

##
🚧 Note: This repository is under active development and continuously updated.
