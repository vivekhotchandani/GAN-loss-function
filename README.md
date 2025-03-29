# GAN Loss Function 

## Overview
This repository explores different loss functions used in Generative Adversarial Networks (GANs). It provides implementations, experiments, and sample results to analyze how various loss functions impact GAN training and performance.

### Repository Structure
- `models/` - Contains implementations of different GAN models with various loss functions.
- `samples/` - Includes generated images and training logs for analysis.
- `gans-4.ipynb` - A Jupyter Notebook containing experiments and results.

## Models Branch
The `models` branch contains implementations of GAN architectures with different loss functions, such as:
- **Standard GAN Loss** (Minimax)
- **Least Squares GAN (LS-GAN)**
- **Wasserstein GAN (WGAN)**
- **WGAN-GP (Gradient Penalty)**

Each model is implemented in PyTorch/TensorFlow and demonstrates how loss functions impact training stability and generated image quality.

## Samples Branch
The `samples` branch contains:
- Example outputs from different GAN models.
- Training logs and loss curves to analyze model performance.
- Visual comparisons of results across different loss functions.

## Getting Started
### Prerequisites
- Python 3.x
- PyTorch or TensorFlow
- OpenCV, NumPy, Matplotlib (for visualization)

### Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/vivekhotchandani/GAN-loss-function.git
cd GAN-loss-function
pip install -r requirements.txt
```

## Usage
Run the Jupyter Notebook to train and analyze GAN models:
```bash
jupyter notebook gans-4.ipynb
```

## Contributions
Contributions are welcome! If you want to add new loss functions or improve existing implementations, feel free to submit a pull request.

## License
This repository is open-source and available for educational and research purposes.

