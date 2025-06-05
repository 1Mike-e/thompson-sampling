# Thompson Sampling for Ads Click-Through Rate Optimization

This project demonstrates the implementation of the **Thompson Sampling** algorithm to solve the Multi-Armed Bandit problem using a dataset of ad click-through rates.

## Overview

Thompson Sampling is a probabilistic algorithm used for balancing exploration and exploitation in reinforcement learning. In this example, the algorithm is applied to select the most effective online advertisement based on historical user interaction data.

## Dataset

The dataset used is `Ads_CTR_Optimisation.csv`, which contains binary feedback (1 for a click, 0 for no click) from users exposed to 10 different ads over 10,000 rounds.

## Requirements

- Python 3.x
- `numpy`
- `matplotlib`
- `pandas`

Install the required packages via pip:

```bash
pip install numpy matplotlib pandas
