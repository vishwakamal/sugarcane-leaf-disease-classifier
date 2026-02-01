# Sugarcane Leaf Disease Classifier

Deep learning model to classify sugarcane leaf diseases using ResNet-18 and PyTorch.

## Classes
- Healthy
- Mosaic
- RedRot
- Rust
- Yellow

## Results
- Test Accuracy: 85%
- Model: ResNet-18 (Pre-trained on ImageNet)
- Framework: PyTorch

## Usage
1. Place images in `data/` folder
2. Run `simple_notebook.ipynb`
3. Model saves to `best_model.pth`

## Requirements
- Python 3.8+
- PyTorch
- Torchvision
- Scikit-learn
- Matplotlib