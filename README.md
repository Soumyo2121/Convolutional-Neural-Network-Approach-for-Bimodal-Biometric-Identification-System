# Convolutional-Neural-Network-Approach-for-Bimodal-Biometric-Identification-System
This is a Convolutional Neural Network Approach for Bimodal (Face and Fingerprint) Biometric Identification System.  
All the necessary software requirements are provided in requirments.txt file.  
However, we have not provided the dataset here as we had to make our own dataset. So you'll also have to create your own dataset.  
The steps for creating the new face dataset is included in the faceid.pynb file. However you'll have to use fingerprint scanner to construct your fingerprint dataset. We have also used labeled faced in the wild dataset which can be found here http://vis-www.cs.umass.edu/lfw/#download .   
At first, you'll have to download the code as zip file and extract the code files from it. The installation steps for necessary packages are given below:  
But before that, a small piece of advice, you should have GPU in your laptop/desktop to train this model successfully and in less time. Otherwise, it may take a day to run.  
1. You must have Python installed. You can download it from here https://www.python.org/downloads/. Don't forget to add in path while installing.  
2. Make sure you have Anaconda installed with Jupyter notebook. You can download anaconda from here https://www.anaconda.com/download . Add to path while installing.
3. This is an optional step. You can install virtual environment using command "pip install virtualenv".Now check your installation using "virtualenv --version" Now, open the  terminal and create a virtual environment using the command, "virtualenv virtualenv_name" After this command, a folder named virtualenv_name will be created. Now at last we just need to activate it, using command "$ source virtualenv_name/bin/activate".
4.  In the virtual environment, you need to install opencv using the command, "pip install opencv-python". Numpy and most of the other packages are included in Anaconda by default, so no need to worry about them.
5.  Now you need to install tensorflow by using the command "pip install tensorflow" . After tensorflow is installed, open anaconda navigator and install jupyter notebook for your virtual environment.
6.  Now you need to open jupyter notebook fro your virtual environment and open the code files.
