# Project Overview

This repository provides a framework for training and evaluating embedding models, with a focus on flexibility and ease of use. The project is organized into two main modules: `train` for model training and `evaluation` for model assessment.

---

## Directory Structure

- **`train/`**: This directory contains all scripts and resources related to training embedding models.
    - **`ft.sh`**: The main script for initiating the training process. You can modify this script to specify the training model and the dataset to be used.
- **`evaluation/`**: This directory houses scripts and resources for evaluating the performance of trained embedding models.
    - **`eval.sh`**: The primary script for running evaluations. This script allows you to configure the embedding model to be evaluated, the directory where the resulting embeddings will be saved, and the dataset to be used for evaluation.
- **`requirements.txt`**: This file lists all Python dependencies required for both the training and evaluation modules.

---

## Environment Setup

Before running any scripts, it is crucial to set up the Python environment with the necessary packages. You can install all required dependencies by running the following command in your terminal:

```bash
pip install -r requirements.txt