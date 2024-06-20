
# Quantum Machine Learning with Quantum Embedding Kernels (QEKs)

This project focuses on developing a quantum machine learning model using Quantum Embedding Kernels (QEKs) for a binary classification task. The project involves the implementation of quantum feature maps, optimization of variational parameters, and training of a classical SVM classifier using the QEK matrix.

The dataset used in this project is the double moons dataset, which is a synthetic dataset commonly used for binary classification tasks. 

Quantum Feature Map :-

This section includes the implementation of a parameterized quantum circuit for embedding data into quantum states. The quantum feature map is designed to transform classical data into a quantum Hilbert space.


QEK Matrix Computation :-

Computation of the QEK matrix involves calculating the inner products of quantum states corresponding to the input data points. This matrix serves as the kernel for the SVM classifier.

Optimization :-

The variational parameters of the quantum feature map are optimized by maximizing the kernel-target alignment. This step ensures that the quantum feature map is tailored to the specific dataset and classification task.

Noise Mitigation and Regularization :-

Techniques such as noise mitigation and regularization are applied to improve the quality of the QEK matrix, addressing issues such as quantum noise and overfitting.

Training the SVM Classifier :-

The SVM classifier is trained using the optimized QEK matrix. This classical machine learning model leverages the quantum-enhanced kernel for improved performance on the binary classification task.

