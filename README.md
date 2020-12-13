# M-RNN-from-scratch

In this repo you can find my implementation of the paper "Estimating Missing Data in Temporal Data Streams Using Multi-directional Recurrent Neural Networks" by Jinsung Yoon, William R. Zame and Mihaela van der Schaar [Paper](https://arxiv.org/abs/1711.08742). The paper introduces an adapted RNN model that can be used to interpolate and impute missing values in temporal data. 

In a Jupyter Notebook "MRNN.ipynb" I try to show the intuitions behind the method and explain the maths. You can follow the notebook step by step with a small example. In the end, a ready to use PyTorch implementation of the method is introduced. You can also find the Notebook on [Kaggle](https://www.kaggle.com/markwallbang/m-rnn-from-scratch). If you have any questions or remarks don't hesitate to drop me a message under simon.boeder@gmail.com. 

If you just want to apply the method of the paper, you can clone the Tensorflow implementations of the authors themselves [Github](https://github.com/jsyoon0823/MRNN).

## Usage

You simply need to run the "MRNN.ipynb" file. The other files are assets used in the notebook like images, a dataset and utility code.
