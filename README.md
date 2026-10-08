# DyUn-TD: Dynamic Uncertainty-Based Data Pruning with Temporal Dual-Depth Scoring

**MSc Thesis — University of Tehran, 2025**

**Author:** Bahar Niknam

## Overview

This repository contains the MSc thesis **“Large-scale Dataset Pruning with Dynamic Uncertainty for Image Analysis”**, which introduces **DyUn-TD (Dynamic Uncertainty-Based Data Pruning with Temporal Dual-Depth Scoring)**.

The work investigates data pruning based on training-time uncertainty and temporal changes in model predictions, with the goal of identifying less informative training samples while retaining a compact and representative subset of the dataset.

## Method

DyUn-TD uses the evolution of model predictions during training to characterize sample informativeness. The framework incorporates:

* Training-time uncertainty estimation
* Temporal changes in model predictions
* Dual-depth scoring for sample selection
* Data pruning under different retention ratios

## Experiments

The proposed approach was evaluated on:

* **CIFAR-10**
* **CIFAR-100**

Experiments were conducted using multiple deep learning architectures and included comparative evaluations and ablation studies.

## Thesis

The complete MSc thesis is available in this repository:

**[MSc Thesis PDF](./MSc_Thesis_Bahar_Niknam.pdf)**

## Academic Information

**Degree:** M.Sc. in Mathematical Statistics
**Institution:** University of Tehran
**Thesis:** Large-scale Dataset Pruning with Dynamic Uncertainty for Image Analysis
**Year:** 2026
