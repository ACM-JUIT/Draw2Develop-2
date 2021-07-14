# Draw2Develop-2 - Deep Learning & Web Dev
A web application where you upload pictorial drawings of major HTML components which are transformed into a single page website via Deep Learning.

## Features
- Single Page Website with minimal but professional frontend.
- Pictoral Representation : A paper drawing with major HTML componets (nav, aside, main and footer) as dataset. ( you are free to create a dataset except mentioned componets as per your imagination but the basis goal of project must remain intact )
- Deep Learning Model : A trained DL model to capture drawn components.
- HTML Part : modular HTML componets with minimal CSS wich are independent and can be mixed with each other to create a web page.

## Model:
We made a output website with HTML and CSS.
- Libraries Used
  - <b>TensorFlow</b> : TensorFlow is a free and open-source software library for machine learning. It can be used across a range of tasks but has a particular focus on training and inference of deep neural networks.
  - <b>TensorFlow (Keras)</b> : Keras is a deep learning API written in Python, running on top of the machine learning platform TensorFlow. It was developed with a focus on enabling fast experimentation. Being able to go from idea to result as fast as possible is key to doing good research. Keras is: Simple -- but not simplistic.
- <b>Machine Learning:</b> 
  - Logistic regression (Supervised) : Logistic regression is a supervised learning classification algorithm used to predict the probability of a target variable. ... In simple words, the dependent variable is binary in nature having data coded as either 1 (stands for success/yes) or 0 (stands for failure/no).
- <b>Deep Learning:</b> In deep learning we implemented <b>CNN (Convolutional Neural Network)</b> which is a class of deep neural network that is used for Computer Vision or analyzing visual imagery.

## Dataset:
We created 100+ handdrawn datasets with complete variations i.e., with complete and incomplete components.
| COMPLETE COMPONENTS      | INCOMPLETE COMPONENTS      |
|------------|-------------|
| <img src="https://github.com/RakshitKumar04/Draw2Develop-2/blob/main/Images/Images/0092.jpg" width="350"> | <img src="https://github.com/RakshitKumar04/Draw2Develop-2/blob/main/Images/Images/0052.jpg" width="350"> |

## Result:
Val_loss is 1.3

| COMPLETE DATASET      | INCOMPLETE DATASET      |
|------------|-------------|
| <img src="https://github.com/RakshitKumar04/Draw2Develop-2/blob/main/loss%20results/model%20with%20balanced%20dataset.png" width="350"> | <img src="https://github.com/RakshitKumar04/Draw2Develop-2/blob/main/loss%20results/model%20with%20less%20full%20images.png" width="350"> |

## Libraries Used
- <b>pandas</b> : pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series.
- <b>NumPy</b> : NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays
- <b>Matplotlib</b> : Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits like Tkinter, wxPython, Qt, or GTK.
- <b>PIL</b> : Python Imaging Library is a free and open-source additional library for the Python programming language that adds support for opening, manipulating, and saving many different image file formats.
- <b>TensorFlow</b> : TensorFlow is a free and open-source software library for machine learning. It can be used across a range of tasks but has a particular focus on training and inference of deep neural networks.
- <b>OS</b> : The OS module in Python provides functions for interacting with the operating system. OS comes under Python’s standard utility modules. This module provides a portable way of using operating system dependent functionality. The *os* and *os.path* modules include many functions to interact with the file system.
- <b>Date Time</b> : In Python, date and time are not a data type of its own, but a module named datetime can be imported to work with the date as well as time. Datetime module comes built into Python, so there is no need to install it externally. 
Datetime module supplies classes to work with date and time. These classes provide a number of functions to deal with dates, times and time intervals. Date and datetime are an object in Python, so when you manipulate them, you are actually manipulating objects and not string or timestamps. 
