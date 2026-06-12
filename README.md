# Automated respiratory disease detection from cough sounds using Deep Learning

This project detects various respiratory diseases using deep learning models. It uses a dataset of cough recordings to train and evaluate the model.

## Features

- Disease detection from cough sounds
- Train, test, and validation splits
- Multiple deep learning models
- Confusion matrix visualization
- Class-wise performance metrics

## Setup

1. Clone the repository
2. Install dependencies from `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To train the model:
```bash
python train.py
```

## Dataset

The dataset is located in the `audio_classification` folder and contains cough recordings for different respiratory diseases.

## Model Architecture

The project uses a custom deep learning model with:
- 1D Convolutional layers
- Batch Normalization
- Dropout
- Fully Connected layers
- Softmax activation

## Results

Results from the evaluation are saved in the `results` folder including:
- Accuracy, precision, recall, f1-score
- Confusion matrix
- Per-class metrics

## License

This project is licensed under the MIT License.