# CNN Image Classification on Custom Dataset

This project implements a convolutional neural network (CNN) for image classification on a custom dataset. It demonstrates data loading, model building, training, and evaluation in PyTorch with a focus on reproducibility and performance metrics.

## 🖼️ Dataset

- A ZIP archive containing the image dataset is extracted and used for training/testing
- Directory structure follows the format: `/class_name/image.png`

## 🔧 Features

- Custom `Dataset` class for PyTorch
- Seed setting for reproducibility
- CNN architecture with configurable layers
- Training and validation with progress bars (`tqdm`)
- Evaluation using precision, recall, F1-score, and confusion matrix
- Summary view with `torchsummary`

## 🧪 Evaluation Metrics

- Accuracy
- Precision / Recall / F1-Score
- Confusion Matrix
- Loss and Accuracy Curves

## 🧰 Requirements

```bash
pip install torch torchvision matplotlib seaborn scikit-learn tqdm pillow
