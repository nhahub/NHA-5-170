# Traffic Sign Recognition System

DEPI graduation project for traffic sign recognition using computer vision and deep learning.

## Project Goals

- Detect and classify traffic signs from images.
- Prepare and preprocess the traffic sign dataset.
- Train a deep learning classification model.
- Evaluate model performance using appropriate metrics.
- Provide an inference pipeline for predicting traffic signs from new images.

## Project Structure

```text
data/
|-- raw/              # Original dataset files
`-- processed/        # Processed dataset files

models/               # Trained model artifacts
notebooks/            # Experiments and exploration
scripts/              # Utility and execution scripts

src/
|-- data/             # Dataset loading and preprocessing
|-- models/            # Model definitions
|-- training/          # Training pipeline
|-- evaluation/       # Evaluation and metrics
`-- inference/        # Prediction pipeline

tests/                # Automated tests
docs/                 # Project documentation
```

## Development Environment

- Python 3.12
- PyTorch
- Torchvision
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## Development Workflow

- Development and testing can be performed locally.
- Model training will use a GPU environment such as Google Colab or Kaggle when required.
- Large datasets, trained models, checkpoints, and experiment outputs are intentionally excluded from Git.