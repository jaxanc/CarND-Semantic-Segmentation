# Semantic Segmentation

## Hyper parameters used

- keep probability: 0.7
- learning rate: 0.0005
- epochs: 50
- batch: 16

## Samples

![alt text][sample001]
![alt text][sample002]
![alt text][sample003]
![alt text][sample004]
![alt text][sample005]
![alt text][sample006]
![alt text][sample007]
![alt text][sample008]
![alt text][sample009]

[sample001]: sample001.png "sample001"
[sample002]: sample002.png "sample002"
[sample003]: sample003.png "sample003"
[sample004]: sample004.png "sample004"
[sample005]: sample005.png "sample005"
[sample006]: sample006.png "sample006"
[sample007]: sample007.png "sample007"
[sample008]: sample008.png "sample008"
[sample009]: sample009.png "sample009"

### Introduction

In this project, you'll label the pixels of a road in images using a Fully Convolutional Network (FCN).

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

### Start
##### Implement
Implement the code in the `main.py` module indicated by the "TODO" comments.
The comments indicated with "OPTIONAL" tag are not required to complete.
##### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.

### Submission
1. Ensure you've passed all the unit tests.
2. Ensure you pass all points on [the rubric](https://review.udacity.com/#!/rubrics/989/view).
3. Submit the following in a zip file.
 - `helper.py`
 - `main.py`
 - `project_tests.py`
 - Newest inference images from `runs` folder  (**all images from the most recent run**)
 
 ## How to write a README
A well written README file can enhance your project and portfolio.  Develop your abilities to create professional README files by completing [this free course](https://www.udacity.com/course/writing-readmes--ud777).
