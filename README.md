# Image Recognition with Quantum LeNet


<div align="center">
    <a href="https://colab.research.google.com/github/reshalfahsi/quantum-lenet/blob/master/Image_Recognition_with_Quantum_LeNet.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="colab"></a>
    <br />
</div>


<p align="center"> <img src="https://github.com/reshalfahsi/quantum-lenet/blob/master/assets/quantum-lenet.png" alt="quantum-lenet" > <br /> The Quantum LeNet model. The quantum layer consists of embedding, quantum circuits, and measurement. </p>


Quantum computing has shaped our future hope of accomplishing calculations one million times faster than before. Its uses have influenced many things, including machine learning. Such collaboration, known as quantum machine learning (QML), has allowed quantum computers to perform a variety of machine learning tasks. In this project, we will look at how a quantum-based deep-learning model performs image classification on the MNIST dataset. The quantum-based model is a combination of classical and quantum layers. The model is based on LeNet and includes a quantum fully connected layer. The classical and quantum layers are implemented using PyTorch and PennyLane, respectively.


## Experiment

Entangle yourself with the implementation using the following [link](https://github.com/reshalfahsi/quantum-lenet/blob/master/Image_Recognition_with_Quantum_LeNet.ipynb) to see the experiment in action.


## Result

## Quantitative Result

The following table displays the quantitative outcomes.

Test Metric | Score |
----------- | ----- |
Accuracy | 96.40%
Loss | 0.364


## Accuracy and Loss Curves

<p align="center"> <img src="https://github.com/reshalfahsi/quantum-lenet/blob/master/assets/loss_curve.png" alt="loss_curve" > <br /> The model's loss curve on the train and validation sets. </p>

<p align="center"> <img src="https://github.com/reshalfahsi/quantum-lenet/blob/master/assets/acc_curve.png" alt="acc_curve" > <br /> The model's accuracy curve on the train and validation sets. </p>


## Qualitative Result

Here, the qualitative results are laid out in the image grid format.

<p align="center"> <img src="https://github.com/reshalfahsi/quantum-lenet/blob/master/assets/qualitative.png" alt="qualitative" > <br /> Nine of ten MNIST digits have their corresponding input images along with the predicted and ground-truth labels exposed to view. </p>



## Credit

- [Gradient-Based Learning Applied to Document Recognition](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf)
- [PennyLane: Automatic differentiation of hybrid quantum-classical computations](https://arxiv.org/pdf/1811.04968)
- [Turning quantum nodes into Torch Layers](https://pennylane.ai/qml/demos/tutorial_qnn_module_torch)
- [PyTorch Lightning](https://lightning.ai/docs/pytorch/latest/)
