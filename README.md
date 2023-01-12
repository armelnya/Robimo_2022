# Robimo_2022
Undergroung object detection via XYZ point clouds, Classifiy Ground points and Off_Ground points.
![Result_1](/home/lorraineshunie/RobimoCode/Result_1.png)
# Experiment Results
The objective of this project is to detect unlabelled underground objects from dereferenced data.
Our method contains many stages:
1. We need to construct a graph with these main parameters, including Adjacent Matrix and Incident Matrix.
2. Creating our customer dataset
3.  Development of a GCN (Graph Convolution Network) model.
3. Implementation of the learning loop.We can see the result file.
## Setup 
### Prerequisite 
1.   Python/extension compiler latest version
2.   Tensorflow:gpu python3:6
3.   Import necessary Libraries
4.   We have to install the Modul (Spektral): which is a python library capable of helping us to creat GCN from raw data.
### Workflow organisation
1. Preproccessing first step data located in the Folder fun
2. Preproccessing second step located in the Folder Fun_2
3. Concepted your Architektur Network with combine Pix2Pix und U_net
4. Training your Architektur Network.
5. Evaluated your Network
### Train a Model
To be able to train model a neuron network, we are need to activate virtual environment tf-gpu.

- python3  path/to/Model_train.py
### Evaluation a Model
To be able to evaluate a model neuronal network, we are also need to activate virtual environment tf-gpu.

- python3  path/to/Model_Evaluate.py
### Developement tools
1.  Python=3.6
2.  Anaconda
3.  Tensorflow/tensorflow:latest-gpu-py3 
4.  Keras 
### Documentation
   
1.  <https://www.tensorflow.org>.
2.  <https://keras.io>.
3.  <https://www.python.org>.
4.  <https://sdv.dev/SDV/user_guides/single_table/ctgan.html>.
5.  <https://scikit-image.org/docs/dev/auto_examples/transform/plot_radon_transform.html>.
