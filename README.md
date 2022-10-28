# Binary-Image-Classification-On-Fashion-MNIST-Using-Tensorflow-Quantum-And-Cirq

**We shall perform Quantum Machine Learning(QML) on Fashion MNIST dataset which contains 10 labels using TensorFLow Quantum and Cirq.Fashion-MNIST is intended to serve as a direct drop-in replacement for the original MNIST dataset to benchmark machine learning algorithms, as it shares the same image size and the structure of training and testing splits.**

[TensorFlow-Quantum](https://www.tensorflow.org/quantum) is a great place to start learning QML and get into this amazing field. TensorFlow Quantum (TFQ) is a quantum machine learning library for rapid prototyping of hybrid quantum-classical ML models.TensorFlow Quantum focuses on quantum data and building hybrid quantum-classical models. It integrates quantum computing algorithms and logic designed in Cirq, and provides quantum computing primitives compatible with existing TensorFlow APIs, along with high-performance quantum circuit simulators.

[Cirq](https://quantumai.google/cirq) is a Python software library for writing, manipulating, and optimizing quantum circuits, and then running them on quantum computers and quantum simulators. Cirq provides useful abstractions for dealing with today’s noisy intermediate-scale quantum computers, where details of the hardware are vital to achieving state-of-the-art results.


We will modify the Fashion MNIST dataset by making classification on only two classes - T-shirt and Shirt. The reason to choose these classes is that they are similar to each other and therefore, it ascertains that the classification problem doesn't become very easy. The image shape in the provided dataset is (28,28), but we need to downscale the images to classify them using QML due to the hardware restrictions. We will downscale the images so that they have the shape (4,4).

In this Project,

Number of Images in the Train Dataset - **10200**

Number of Images in the Validation Dataset - **1800**

Number of Images in the Test Dataset - **2000**

Size of each Image - **(2,2)**

Type of Image - **Grayscale Image**

Number of Labels - **2**

 | **Label** | **Description**   |
  |------|------|
  |   **0**  | **Tshirt/top**|
  |   **6**  | **Shirt** |  

Checkout the Dataset [Here](https://www.kaggle.com/datasets/zalando-research/fashionmnist)
