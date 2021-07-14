# Draw2Develop-2 - Deep Learning & Web Dev
A web application where you upload pictorial drawings of major HTML components which are transformed into a single page website via Deep Learning.

## Features
- Single Page Website with minimal but professional frontend.
- Pictoral Representation : A paper drawing with major HTML componets (nav, aside, main and footer) as dataset. ( you are free to create a dataset except mentioned componets as per your imagination but the basis goal of project must remain intact )
- Deep Learning Model : A trained DL model to capture drawn components.
- HTML Part : modular HTML componets with minimal CSS wich are independent and can be mixed with each other to create a web page.

## Model:
We made a output website with HTML and CSS.
- ### Libraries Used
  - <b>TensorFlow</b> : TensorFlow is a free and open-source software library for machine learning. It can be used across a range of tasks but has a particular focus on training and inference of deep neural networks.
  - <b>TensorFlow (Keras)</b> : Keras is a deep learning API written in Python, running on top of the machine learning platform TensorFlow. It was developed with a focus on enabling fast experimentation. Being able to go from idea to result as fast as possible is key to doing good research. Keras is: Simple -- but not simplistic.
- ### <b>Machine Learning:</b> 
  - ELU : The Exponential Linear Unit (ELU) is an activation function for neural networks. In contrast to ReLUs, ELUs have negative values which allows them to push mean unit activations closer to zero like batch normalization but with lower computational complexity.<br></br>
    <img src="https://github.com/RakshitKumar04/Draw2Develop-2/blob/main/Activation%20function/Screenshot%202021-07-14%20185600.png" width="350">
  - ReLU : The rectified linear activation function (called ReLU) has been shown to lead to very high-performance networks. This function takes a single number as an input, returning 0 if the input is negative, and the input if the input is positive.<br></br>
    <img src="https://github.com/RakshitKumar04/Draw2Develop-2/blob/main/Activation%20function/Screenshot%202021-07-14%20185627.png" width="350">
  - Sigmoid : The sigmoid function is a mathematical logistic function. It is commonly used in statistics, audio signal processing, biochemistry, and the activation function in artificial neurons. The formula for the sigmoid function is F(x) = 1/(1 + e^(-x)).<br></br>
    <img src="https://github.com/RakshitKumar04/Draw2Develop-2/blob/main/Activation%20function/Screenshot%202021-07-14%20185446.png" width="350">
- ### <b>Deep Learning:</b> 
  - In deep learning we implemented <b>CNN (Convolutional Neural Network)</b> which is a class of deep neural network that is used for Computer Vision or analyzing visual imagery.

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

| DATASET      | ORDER OF RESULT      |
|------------|-------------|
| <img src="https://github.com/RakshitKumar04/Draw2Develop-2/blob/main/Images/Images/0082.jpg" width="350"> | Navbar-> sidebar-> footer-> main  |
