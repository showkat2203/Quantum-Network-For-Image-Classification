##### Convolutional neural networks (CNNs) are widely utilized in machine learning (ML) models with the ability to extract features from massive quantities of data in a hierarchical way via several transformation layers. Therefore, our goal was to develop a faster and more efficient transformational layer namely quantum convolutional or quanvolutional layer for an image processing task.  The transformed data from the quantum circuit  used for generating meaningful features for the image classification. Thus, this work focused on utilizing CNNs and quantum convolutional neural networks (QCNNs) on the MNIST image dataset to assess the potential impact of the quantum transformations for image classification. 


##### To use quantum circuits for image detection, we had to undergo numerous steps. We preprocessed the raw data after collecting the image data for classification. This preprocessing includes removing images with low resolution, choosing pixel sizes, etc. In addition, we reviewed prior studies on image classification using deep neural networks to determine the appropriate hyperparameter value. Then, for our QCNN model, we constructed a quantum circuit and processed the input data into the transformation layer. Besides this, we computed the accuracy and loss value using the traditional CNN model for image recognition. Finally,  we calculated the accuracy, loss value, and runtime for our QCNN model and compared the classification performance of the two models. As this study used a quantum algorithm, hence, a basic understanding of the components of quantum computing will make it easier to understand the recognition process.


# References<a name="references"></a>

[1] Chao Yang, Wenxiang Jiang, and Zhongwen Guo. Time series data classification based on dual path cnn-rnn cascade network. IEEE Access, 7:155304155312, 2019.

[2] Kosuke Mitarai, Makoto Negoro, Masahiro Kitagawa, and Keisuke Fujii. Quantum circuit learning. Physical Review A, 98(3):032309, 2018.

[3] Soronzonbold Otgonbaatar and Mihai Datcu. Classification of remote sensing images with parameterized quantum gates. IEEE Geoscience and Remote Sensing Letters, 19:1–5, 2021.

[4] Quanvolutional Neural Networks using Pennylane (https://pennylane.ai/qml/demos/tutorial_quanvolution.html)

[5] Maxwell Henderson, Samriddhi Shakya, Shashindra Pradhan, and Tristan Cook. Quanvolutional neural networks: powering image recognition with quantum circuits. Quantum Machine Intelligence, 2(1):1–9, 2020.

[6] How to Develop a CNN for MNIST Handwritten Digit Classification (https://machinelearningmastery.com/how-to-develop-a-convolutional-neural-network-from-scratch-for-mnist-handwritten-digit-classification/)
