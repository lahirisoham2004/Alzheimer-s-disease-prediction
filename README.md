# Alzheimer Disease Prediction

This repository contains various models implemented for predicting Alzheimer’s disease using MRI images. It includes competing models based on established architectures as well as a proposed hybrid model that combines DINOv2 and Kolmogorov-Arnold Networks (KAN). 

## Table of Contents

- [Introduction](#introduction)
- [Repository Structure](#repository-structure)
- [Competing Models](#competing-models)
- [Proposed Model](#proposed-model)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Alzheimer's disease (AD) is a progressive neurodegenerative disorder that affects millions of individuals worldwide. Early detection and accurate diagnosis are crucial for effective intervention. This work explores various deep learning models to enhance the accuracy of Alzheimer’s disease prediction using medical imaging data.

## Repository Structure
```md
Alzheimer-disease-prediction/
├── MODELS/
│   └── COMPETING MODELS/
│       ├── Alznet.ipynb
│       ├── HTLML.ipynb
│       ├── Modified Alexnet.ipynb
│       ├── Modified Inception.ipynb
│       ├── Resnet18.ipynb
│       ├── Resnet50.ipynb
│       ├── VGG16.ipynb
│       ├── VGG19.ipynb
│       └── ViTBiLSTM.ipynb
└── PROPOSED MODEL/
    └── Dinov2KAN.ipynb

```
### Competing Models

The `COMPETING MODELS` folder includes various well-known deep learning architectures that have been utilized to predict Alzheimer’s disease. Each model is implemented in a Jupyter Notebook and can be executed independently.

### Proposed Model

The `PROPOSED MODEL` folder features the **DINOv2-KAN** hybrid model, which combines vision transformers with Kolmogorov-Arnold Networks to enhance predictive performance. This notebook outlines the architecture, training process, and evaluation metrics.

## Getting Started

To get started with this repository:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Alzheimer-disease-prediction.git
   cd Alzheimer-disease-prediction

2. **Install the required dependencies:** 
   Make sure you have Python and pip installed, then run:
   ```bash
    pip install -r requirements.txt
3. **Run the notebooks:** 
   Open Jupyter Notebook or JupyterLab, navigate to the desired model's notebook, and execute the cells to train and evaluate the model.
   
## Contributing

We welcome contributions to improve this project. If you have suggestions or enhancements, please create an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.





