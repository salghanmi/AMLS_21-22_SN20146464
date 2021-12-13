# ML_Coursework
Note: Some files not uploaded in the Github due to its big size, so please check the Google Drive link ---> ( https://drive.google.com/drive/folders/1Zvz9BSzqv0mrjBaWSCrJ7-mZQ_6DTSfp?usp=sharing ) where you can finds all the files 


Introduction of the project: 

This repository contains the code of the coursework of the ELEC0134 Applied Machine Learning Systems module at UCL. The aim of this project is to classification the Brain Tumor images. The dataset used in this project is an image-based dataset containing MRI scans of the human brain. The images are grayscale and are classified into four classes based on tumour type. Prepossessing techniques were applied in these data and used as an input for all machine learning models in this repository. 

Citation: 
Sartaj Bhuvaji, Ankita Kadam, Prajakta Bhumkar, Sameer Dedge, and Swati Kanchan, “Brain Tumor Classification (MRI).” Kaggle, 2020, doi: 10.34740/KAGGLE/DSV/1183165. 

There are two main tasks in this project: 
	Task 1: 
    	The binary task includes building a classifier to identify a tumour in the MRI images. 
	Task 2: 
    	The Multiclass task is to build a classifier to identify the type of tumour in each MRI image (meningioma tumour, glioma tumour, pituitary tumour or no tumour). 

Separated models designed for each task are as follow:
    Task 1: This task was implemented with four models: SVM, RF, DT, and CNN. 
    Task 2: Data Augmentation used in CNN models.

The file of this repository organised as follow: 
 * ML_Courswork: 
	* README.md : Contain some information about the repository 
	* Task 1 Folder : This folder have all the file of task 1 which are: 
	
		± Task 1 SVM.ipynb: this python file for SVM used in this task 
		
		± Task 1- Random Forest Classiffier.ipynb: this python file for FR used in this task 
		
		± Task 1 using Decision tree.ipynb: this python file for DT used in this task 
		
		± Task 1 Deep Learning Final version.ipynb : this python file for CNN used in this task 
		
		± Test Result CNN Task1.ipynb: This file for testing the CNN model 
		
		± Test Result ML Task1.ipynb: this file have the result of SVM, RF and DT 
		
		± All the above models saved in sac format  (Note Some of the Saved models not uploeaded in Githud because it have big size, you can found it in the Google Drive using the link at the end of this file)
	* Task 2 Folder 
		± Taks_2.ipynb: this python file of implement task 2 using CNN 
		
		± Test Result CNN Task 2.ipynb:This file for testing the CNN model in the task 2
		
		± Saved model for the second task. (some of the models saved is missing in Github due to its big size you can finds all the missing files in Google Drive see the like at the end of this file)
		
	* dataset.zip : This zip file contains the pre- proccesed of train images and its label ( you can find this folder in Google Drive due it bug size its not uploaded in Github ) 
	* test.zip : This zip file contains the pre- processed of test images and its label
	* Pre-Procces.ipyb : This python file contain the pre- procces code (this file is not uploaded in Github due to its big size you can finds all the missing files in Google Drive see the like at the end of this file)


Steps For Running the Code: 

1. Download the the files of the project
2. Make sure that all the required libraries are installed, if it not installed you can install in using pip 
3. Change the file of the data in each python notebook 
4. Run the file 

Necessary packages or header files: 
sklearn, Pandas, numpy, matplotlib.pyplot, openCV , pickle, warnings, os , and Tensorflow for Keras 

	
Google Drive link ---> ( https://drive.google.com/drive/folders/1Zvz9BSzqv0mrjBaWSCrJ7-mZQ_6DTSfp?usp=sharing )




