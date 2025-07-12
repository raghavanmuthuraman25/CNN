CNN Middle Layers Visualization & Architecture Modification

This repository demonstrates how to analyze and improve Convolutional Neural Networks (CNNs) by visualizing internal representations and experimenting with architectural changes—including attention mechanisms.

📚 Project Steps
Each notebook in this repo will:

1. Load Data
Load a chosen dataset directly from Kaggle.

2. Train a Baseline CNN
A simple architecture like:

nginx
Copy
Edit
Conv → ReLU → Pool → Fully Connected
Train the network on the dataset.

Evaluate initial accuracy and loss.

3. Visualizations
3.1 Filters
Visualize learned convolution filters from the first few layers.

3.2 Activation Maps
Show feature maps produced by intermediate layers for selected input images.

3.3 Grad-CAM Heatmaps
Visualize which regions of the input image influence predictions the most.

✅ Hyperparameter Search
Run a small grid or random search over:

Number of filters

Kernel size

Learning rate

Optimizer

Batch size

✅ Architecture Modifications
Explore changes to improve performance or interpretability:

➕ Add/Remove Filters
Experiment with increasing or decreasing the number of filters in layers.

➕ Add SE Attention Block
Insert Squeeze-and-Excitation (SE) blocks to enhance channel-wise attention.

➖ Prune Filters
Remove less-important filters to reduce model size without significantly impacting accuracy.

✅ Retrain & Compare
Retrain the modified architectures.

Compare models:

Accuracy

Loss curves

Grad-CAM visualizations for before vs. after architectural changes.

🔎 Goals
Understand what CNN middle layers learn.

See the effect of attention mechanisms on feature extraction.

Optimize architecture for better performance and interpretability.

🚀 Getting Started
Clone this repo

Install required dependencies

Run each notebook and follow along with the experiments!

