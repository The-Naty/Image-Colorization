# Image Colorization using Capsule and GAN

### Installation Guide

Python 3.6+ is needed to be installed on the system.
After installing Python, the following dependencies are needed to be installed 

- easydict==1.10
- numpy==1.19.5
- Keras==2.1.2
- Pillow==8.4.0
- tensorflow==1.9.0
- imageio==2.5.0

a dataset will be needed to be downloaded. 
The used dataset in this project is Linnaeus 5 

### User Guide
After the project environment is successfully ready and the dataset is downloaded, 
The training options in the main script should be changed accordingly.

-	dataset: Name of the dataset folder created
-	dataset_path: The root folder containing the dataset folder
-	checkpoints_path: The folder where the model will be saved/loaded as well as the testing output will be saved
-	mode: set to 0 for training and 1 for testing
-	batch_size: Training batch size
-	epochs: The number of desired Epochs
-	lr: Learning rate
-	lr_decay: Learning rate decay
-	save_interval: The number of steps before saving the model
-	sample_interval: The number of steps before doing random testing samples
-	sample_size: Sample test size

 

To start training, change the mode to 0 as mentioned above and execute the main.py script 
and make sure the training images are located in the training folder as well as the testing images 
located in the testing folder as mentioned in the installation guide


To start testing, change the mode to 1 as mentioned above and execute the main.py script 
and make sure the testing images are located in the testing folder as mentioned in the installation guide.
The testing process output should look similar to the image below
