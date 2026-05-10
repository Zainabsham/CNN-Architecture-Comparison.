## Datasets

This project uses two image classification datasets:

### CIFAR-10
- Used for training
- Contains 50,000 training images
- Includes 10 object classes

### STL-10
- Used for testing and evaluation
- Contains higher-resolution images
- Used to evaluate cross-dataset generalization


Instructions for Running the Project
Open the notebook in Google Colab.
Enable GPU runtime:
Runtime → Change runtime type → GPU
Install required libraries:
!pip install -q torchmetrics codecarbon thop
Run all notebook cells sequentially.
The notebook will:
Download datasets
Train both CNN models
Evaluate performance
Generate plots and results
Save outputs automatically
