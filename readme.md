# LSTM Text Inference Experiment

This repository contains a Jupyter Notebook and a tokenizer configuration file (`tokenizer.json`) for training a small LSTM-based model for text inference using PyTorch. The project was created as an initial deep learning experiment before moving on to more advanced transformer-based models and large language models (LLMs).

---

## Contents

- **LSTM _neural_network.ipynb**: The main notebook containing the code for data processing, model definition, training (with mixed precision), and evaluation.
- **tokenizer.json**: A JSON file with your tokenizer configuration or saved tokenizer data.
- **README.md**: This file.

---

## Project Overview

In this experiment, I implemented a very small LSTM  model to perform text inference. The model consists of:
- An **Embedding** layer that converts word indices into vector representations.
- The hidden  **LSTM** (Long Short-Term Memory) layers that processes the sequence data.
- A **Fully Connected (Linear)** layer that produces the output logits.

The notebook also demonstrates how to use PyTorch's Automatic Mixed Precision (AMP) with a GradScaler, and it includes basic logging to measure data loading and GPU compute times during training.

---

