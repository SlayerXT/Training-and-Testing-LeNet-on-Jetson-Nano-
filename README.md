# 1. Project Overview
This project includes two deep learning implementations for image classification on the Jetson Nano Developer Kit:

**LeNet model using Caffe framework** to train and evaluate on the classic MNIST dataset.

**Fashion-MNIST classification using Keras.**


# 2.Project Structure
```
.
├── CaffeLenet.pptx                  # Project presentation slides
├── Install caffe guidance.doc       # Setup guide for installing Caffe on Jetson Nano
├── custom_auto_solver.prototxt      # Solver configuration for Caffe
├── custom_auto_train.prototxt       # Training network definition for Caffe
├── custom_auto_test.prototxt        # Testing network definition for Caffe
├── learning-lenet.ipynb             # Jupyter notebook for LeNet training
├── python_confmat.py                # Python layer for confusion matrix in Caffe
└── fashion_MNIST/
    └── fashion_mnist_keras.ipynb    # Fashion-MNIST classification using Keras

```
# 3.Highlights
- 🚀 Jetson Nano compatible setup  
- 🧠 LeNet model training with Caffe  
- 🐍 Custom Python layer for confusion matrix  
- 👗 Fashion-MNIST classification with Keras (for benchmarking)

# 4.Installation (Caffe on Jetson Nano)
See **Install caffe guidance.doc** for detailed setup steps.

# 5.Notes
The **python_confmat.py** script is a custom Python layer for computing the **confusion matrix** and **test accuracy** during evaluation in Caffe.

The **.prototxt** files define the network architecture and training/test parameters for LeNet.

