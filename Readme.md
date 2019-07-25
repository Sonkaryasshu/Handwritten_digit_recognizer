# Handwritten Digit Recognizer
In this project we are going to recognise handwritten digits.  I am using the famous MNIST dataset for this purpose (which include photos of handwritten digits) and neural netowrk( more precisely CNN ) to build the classifier model.


### Introduction
- **MNIST**

	MNIST ("Modified National Institute of Standards and Technology") is the de facto “Hello World” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.
- **Neural network**
	Artificial Neural Networks are used in various classification task like image, audio, words. Different types of Neural Networks are used for different purposes, for example for predicting the sequence of words we use Recurrent Neural Networks more precisely an LSTM, similarly for image classification we use Convolution Neural Network. In this project, I am using  CNN.


### Steps to run it on your system:

**Note:** I am using Ubuntu 18.04 with anaconda environment and python-3.6.8

1. Get this project to your local system

2. Change directory to current project
	>cd handwritten_digit_recognizer

3. Create virtual environment ***[Optional]***  
Using Anaconda here( You may use python venv)  
    **Note:** Use tensorflow as backend in keras
- Use the terminal or an Anaconda Prompt for the following steps:

	> conda create -n myenv python=3.6 keras=2.0.6 tensorflow=1.12.0

- Activate the new environment:

	> conda activate myenv

4. Run the python file

	> python main.py


	**Note:** If you have created a virtual environment , you may leave it by running
	>conda deactivate
#### Additional Requirements:
- good internet connection( If dataset isn't available in your system ).
- GPU availability is a big plus.
