# Transfer-Learning-Models-Scratch

In this project, I've implemented 10 transfer learning models from scratch and visualized their architectures using Graphviz.This Jupyter Notebook contains the implementation of 10 transfer learning models created from scratch using various architectures. Each model is briefly described along with its purpose.

## Models Used
1. AlexNet: A pioneering deep learning model known for its success in the ImageNet Large Scale Visual Recognition Challenge (ILSVRC) 2012.

2. VGG16: A convolutional neural network architecture with a relatively simple and uniform structure, consisting of 16 layers.

3. VGG19: Similar to VGG16 but with 19 layers, providing a slightly deeper architecture.

4. DenseNet121: Dense Convolutional Network, where each layer is connected to every other layer in a feed-forward fashion.

5. DenseNet201: A deeper version of DenseNet, with 201 layers, enabling more powerful feature extraction capabilities.

6. ResNet50: Residual Network, introducing skip connections to address the vanishing gradient problem, particularly effective in very deep networks.

7. MobileNet: Designed for mobile and embedded vision applications, MobileNet offers efficient depth-wise separable convolutions.

8. Xception: Extreme version of Inception, where instead of regular convolutions, depth-wise separable convolutions are used extensively.

9. Inception: Known for its inception modules, which allow the network to learn both spatial and channel-wise feature hierarchies simultaneously.

10. YOLO: (You Only Look Once) Popular object detection algorithm known for its speed and accuracy, processes images in a single pass through the network, making it extremely fast for real-time applications.

## Visualizations

For each model, the architecture is visualized using Graphviz.

```
Install Graphviz: You can download and install Graphviz from its official website.

Add Graphviz to PATH:

After installing Graphviz, find the bin directory where Graphviz is installed. This directory contains the dot executable.
Add this directory to your system's PATH environment variable.
If you're using Windows, you can do this by going to System Properties → Advanced → Environment Variables, then find the PATH variable in the System variables section and edit it to include the Graphviz bin directory.
If you're using Linux or macOS, you can typically achieve this by adding the directory to your .bashrc or .bash_profile file.
```

## Usage:
- Make sure to have the necessary dependencies installed (e.g., TensorFlow, Keras).
- Run each cell sequentially to load the models and generate their visualizations.
- Explore the architectures and understand their structures.

Note: This notebook is intended for educational purposes to demonstrate the implementation of transfer learning models and their visualizations using Graphviz.

