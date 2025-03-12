A PyTorch implementation of a simplified Mamba-inspired neural network model for time series prediction. This project demonstrates the use of a custom recurrent architecture to predict daily minimum temperatures from a publicly available dataset. The model incorporates selective state updates and normalization techniques, trained using MSE loss with Adam optimization. Includes data preprocessing, training pipeline, and visualization of predictions and loss curves using Matplotlib.

Key Features:
- Loads and normalizes daily temperature data from a CSV dataset.
- Implements a custom SimpleMamba module with parameterized state transitions.
- Trains the model on a sequence prediction task with gradient clipping for stability.
- Visualizes ground truth vs. predictions and training loss over epochs.
- Dataset: Daily minimum temperatures (sourced from jbrownlee/Datasets on GitHub).
