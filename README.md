# Semantic Segmentation
### Introduction
This project demonstrates using [FCN 8 architecture by EC Berkeley](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf) (fully convolutional network) for semantic segmentation of road images.
### Setup
##### Frameworks and Packages
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
[Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip). 
The model was implemented in tensorflow, using an adam optimizer and l2 regularization and trained over 2000 epochs. 

Watch the video with the results

[![Watch the video](https://github.com/josealb/CarND-Semantic-Segmentation/blob/master/video.PNG)](https://www.youtube.com/watch?v=W2Q-hBLeQrQ)
