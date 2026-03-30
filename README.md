Fashion-MNIST Classification: Exploring CNN Architectures
This project features a custom Convolutional Neural Network (CNN) built by me to solve the challenge of automated image classification. While traditional Multi-Layer Perceptrons (MLPs) can process images, 
this implementation demonstrates why CNNs are the superior standard for computer vision.

📊 The Problem & Challenges
Recognizing patterns in clothing requires more than just looking at individual pixel intensities. In this project, Giorgi Porchkhidze addressed several key challenges:

Spatial Context: Preventing the loss of 2D information that occurs when flattening images.

Feature Extraction: Understanding the mechanics of Convolution and Pooling layers.

Interpretability: Visualizing the "hidden" learning process of the network.

🎯 Project Objectives
The core of this project, developed by Giorgi Porchkhidze, is built around four pillars:

CNN Architecture Construction: Designing a pipeline using Conv2D for feature detection, MaxPooling for spatial reduction, and Dense layers for final decision-making.

Filter & Feature Map Visualization: Extracting internal weights to see how the network learns to identify edges and complex shapes.

Comparative Analysis (CNN vs. MLP): A benchmark study comparing this model against a standard MLP to prove the efficiency of weight sharing.

Regularization Techniques: Implementing Dropout and Batch Normalization to stabilize and accelerate the training process.

🏗️ The Architecture
The model follows a hierarchical approach:

Convolutional Base: Uses sliding kernels to create feature maps.

Pooling Layer: Reduces resolution, making the model robust to small shifts.

Classifier: A flattened vector fed into fully connected layers with Softmax activation.

📁 Dataset Details
The network was trained on the Fashion-MNIST dataset:

Input: 28×28 grayscale images.

Training Set: 60,000 samples | Test Set: 10,000 samples.

Classes: 10 categories (T-shirt, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot).

👤 Author & Developer
Giorgi Porchkhidze * Architected and trained the neural network.

Implemented visualization logic and regularization layers.

Conducted comparative performance analysis.
