# LLM-based-GA-in-the-domain-of-REE

# Rare Earth Element Prediction: Diffusion Augmentation & LLM-Guided GA

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](./LICENSE)

## 📌 Overview
This repository contains the official implementation of the paper **"Rare Earth Element Prediction Using Diffusion-Based Data Augmentation and LLM-Assisted Genetic Optimization."**

We address the challenge of predicting Rare Earth Elements (REEs) with limited geochemical data by introducing a dual-stage framework:
1.  **Tabular Diffusion Model:** Synthesizes high-fidelity data to overcome data scarcity.
2.  **LLM-Guided Genetic Algorithm:** Uses a Large Language Model to semantically guide the hyperparameter search, replacing blind stochastic operators (crossover/mutation).
