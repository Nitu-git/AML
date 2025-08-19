# FLAME-AI-Challenge-2024
As part of the Advanced Machine Learning coursework (MSBA), we joined the FLAME AI 2024 challenge to tackle wildfire forecasting. The goal was to predict the fireline for 20 future timestamps using just the first 5 frames of data.

# Approach

We explored a mix of classical and deep learning methods to balance accuracy and interpretability:

 - Optical Flow for motion-based tracking

 - XGBoost for fast, tree-based predictions

 - PredFormer (transformer-based architecture)

 - CNN–LSTM hybrids for spatio-temporal learning

 - Physics-Informed Neural Networks (PINNs) to integrate physical constraints into the predictions

# Results

Our models reached a mean squared error (MSE) of ~0.011, showing strong accuracy in predicting wildfire spread patterns.

# How to Run

 - Clone this repository

 - Install dependencies with pip install -r requirements.txt

 - Open any of the .ipynb notebooks in Jupyter/Colab

 - Run cells in sequence to reproduce results for each method (My have to correct source data path)

# Applications

This work can support:

 - Emergency responders with faster and smarter resource allocation

 - Insurers with more reliable wildfire risk modeling

 - Utilities in protecting critical infrastructure from fire damage

# Learn More

Slides and results are included in this repository

Medium write-up: [Forecasting Flames – Spatio-Temporal ML for Wildfires](https://medium.com/@pillai.anjali/forecasting-flames-driving-impact-with-spatio-temporal-ml-53e4f263f17f)
