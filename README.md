# Eye State Detection: Open or Closed

## Project Overview

This project aims to develop a machine learning model that can accurately determine whether a person’s eyes are open or closed. The project involves the following steps:
1. **Data Collection**: Obtaining and processing a dataset of eye images.
2. **Data Augmentation**: Expanding the dataset through augmentation to increase model training data.
3. **Model Training**: Building and training a machine learning model using the dataset.
4. **Evaluation**: Assessing the model's performance and making predictions on random images.

## Folder Structure

```bash
my_project/
│
├── dataset/                  # Contains original and augmented datasets
│   ├── closed_eyes/          # Images of closed eyes
│   └── open_eyes/            # Images of open eyes
│
├── model/                    # Model training code and saved model files
│   └── eye_state_model.h5    # Trained model
│
├── results/                  # Evaluation results including accuracy and loss curves
│   └── accuracy_loss_curves.png  # Accuracy
