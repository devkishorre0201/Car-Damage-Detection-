# Car-Damage-Detection-
Car Damage Detection using PyTorch with ResNet transfer learning, data augmentation, and proper train/val/test splits. Includes evaluation, visualization, and Gradio deployment.

## Features
- Transfer Learning with ResNet (feature extraction & fine-tuning)  
- Data Augmentation & Normalization for robust training  
- Training, Validation, and Test splits for evaluation  
- Accuracy & Loss visualization with Matplotlib  
- Gradio app for interactive predictions  

## Dataset
Source: [Kaggle – Car Damage Detection](https://www.kaggle.com/datasets/anujms/car-damage-detection)  

# Structure:  
data1a/
├── training/
│ ├── 00-damage
│ └── 01-whole
├── validation/
│ ├── 00-damage
│ └── 01-whole
└── test/
├── 00-damage
└── 01-whole


# Results

Model: ResNet (fine-tuned)

Accuracy: ~XX% on test set

Example training/validation plots:
(Insert plots here)

# Future Work

Use larger datasets

Try EfficientNet/ViT for better accuracy

Add severity classification (minor/major damage)
