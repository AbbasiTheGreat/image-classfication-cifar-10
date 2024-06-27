# image-classfication-cifar-10

Project Overview:

Dataset: CIFAR-10

Architecture: Custom CNN with Inception modules

Tools: Keras, TensorFlow, Python

Accuracy Achieved: 92%


🔹 Dataset Description:

The CIFAR-10 dataset is a widely used benchmark dataset in machine learning and computer vision. It consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class. The dataset is divided into 50,000 training images and 10,000 testing images. The 10 classes represent everyday objects and animals, specifically:

Airplane
Automobile
Bird
Cat
Deer
Dog
Frog
Horse
Ship
Truck


🔹 Highlights:

Loading and Preprocessing:

Efficiently loaded the CIFAR-10 dataset and converted the images to float32 type.
Normalized pixel values to the range [0, 1] to improve model training performance.
Applied one-hot encoding to the labels for multi-class classification.

Model Architecture:

Utilized the Inception module, which includes multiple convolutional filters of different sizes, to capture complex patterns and features in the images.
Built the model using Keras Functional API, which provides more flexibility and control over the model architecture.
Added Batch Normalization layers to stabilize and speed up the training process.
Incorporated Dropout layers to prevent overfitting and improve the generalization of the model.

Training:

Trained the model for 100 epochs with a batch size of 64, optimizing the model parameters using the Adam optimizer.
Monitored training and validation performance to ensure the model is learning effectively.

Visualization:

Plotted training and validation loss curves to visualize the model's learning progress and identify any overfitting.
Plotted training and validation accuracy curves to track the model's performance.
Visualized the model's predictions on a subset of test images to compare predicted labels against true labels.

🔹 Benefits of the Inception Module:

Multi-level Feature Extraction: The Inception module captures diverse features at different scales, improving the model's ability to recognize complex patterns in the data.

Reduced Computational Cost: By using multiple filter sizes within the same module, the Inception module efficiently handles varying spatial dimensions in the input images, reducing the overall computational cost.

Enhanced Performance: Proven to boost performance in complex image classification tasks, the Inception module allows for deeper and more effective networks without a significant increase in computational overhead.
