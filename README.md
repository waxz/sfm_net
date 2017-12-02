# sfm_net
SfM-Net: Learning of Structure and Motion from Video

https://arxiv.org/pdf/1704.07804.pdf

==

# Instructions

You can find a model.ipynb file, which can be used as a Jupyter notebook for IPython. It contains the training code for a given video file (.mkv). The code is explained with a few pictures from the paper linked above. However, for more details, please read the paper.

# Running the training

In order to run the code make sure you have the following dependencies installed:

## Dependencies


* Python 3
* Numpy (pip install numpy)
* Matplotlib (pip install matplotlib)
* Pandas (pip install pandas)
* Tensorflow (pip install tensorflow)
* skimage (pip install scikit-image)
* Keras (pip install keras)
* ImageIO (pip install imageio)

## Run training

The easiest way to run the training is to install Jupyter (pip install jupyter) and run its server from which the .ipynb notebook can be opened and executed. Once you have installed Jupyter, just run "jupyter notebook" from a console and your browser should automatically open a connection to the Jupyter server. Simply select the model.ipynb file in your browser and run it. The code contains sample data which is used for training.

# Output

The code generates three files which can be used as a tensorflow model in your code (compare https://www.tensorflow.org/programmers_guide/saved_model).


# Test code

Test code is not available yet.
