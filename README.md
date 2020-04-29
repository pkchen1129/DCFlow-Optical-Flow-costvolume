# EECS 504: Computer Vision Final Project - DCFlow: Optical FLow via Cost Volume Processing
We present an optical flow estimation algorithm described in Accurate Optical Flow via Direct Cost Volume Processing. The project can be divided into two part. The first part describes how to generate feature embedding via a convolutional neural network. The second part is how the 4-dimensional cost volume can be efficiently constructed and stored using the embedding. We conduct experiments on Sintel benchmark to evaluate the cost volume with a winner-take-all matching algorithm. We also show that adding a normalization layer to the CNN model outperforms the original model.

## Files
Our repository contains several files as following:

Final Project: [pdf](https://github.com/pkchen1129/DCFlow-Optical-Flow-costvolume/blob/master/EECS_504_Team9.pdf) <br/>
Training: [Jupyter Notebook](https://github.com/pkchen1129/DCFlow-Optical-Flow-costvolume/blob/master/DCFlow_training.ipynb) <br/>
Evaluation: [Jupyter Notebook](https://github.com/pkchen1129/DCFlow-Optical-Flow-costvolume/blob/master/DCFlow_eval.ipynb) <br/>
Best Model: [.pth](https://github.com/pkchen1129/DCFlow-Optical-Flow-costvolume/blob/master/model/dcflow_state_dict_ep30_200k_normed.pth) <br/>
