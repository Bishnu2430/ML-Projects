# ASL Data Augmentation and Model Prediction

This project extends the ASL alphabet classification pipeline by focusing on two critical stages: data augmentation and model prediction. It demonstrates how image transformations can enhance model robustness and how trained models can be used to predict ASL signs from new data.

## Part 1: Data Augmentation

- Applies various transformations using `torchvision.transforms` to improve dataset diversity
- Visualizes augmented ASL images for better interpretability
- Helps reduce overfitting and improves model generalization

## Part 2: Model Prediction

- Loads a trained CNN model for ASL alphabet recognition
- Makes predictions on test images or new input data
- Visualizes predicted results alongside actual ASL signs

## Requirements

- Python
- PyTorch
- Torchvision
- Matplotlib

## Objective

To enhance classification performance through data augmentation and demonstrate real-time predictions using a trained ASL recognition model.
