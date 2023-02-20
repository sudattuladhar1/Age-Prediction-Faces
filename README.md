# Age_Prediction_of_IMDB_WIKI_face_image
The main objective of the project is to predict the age of celebrities based on their IMDB/WIKI face dataset. Some other objectives includes
	
1. Design and implement different convolutional neural network (CNN) architectures using PyTorch.
2. Use IMDB/WIKI dataset (faces only) for training, testing, and validation of network.
3. Evaluate the performance of designed neural networks.

The project execution involved pre-processing raw data, implementing different CNN architectures, training and testing on IMDB/WIKI dataset and obtain accuracy results on age prediction. 


## Dataset
The raw data for this project are taken from [IMDB-WIKI - 500k+ face images with age and gender labels (ethz.ch)](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/), that contains the images of faces along with the metadata containing informatons as date of birth, year when photo was taken, path of file, gender and others. 

## Procedure
1. Age extraction from dataset (imdbwiki_age.m) - Uses matlab code to extract labels from data
2. Data filtering (Data_filtering.ipynb) - remove the outliers from data
3. Data preprocessing and splitting (data_preprocessing.ipynb, data_splitting.ipynb) - convert all images to 64x64 size, split data to training (60%), testing(20%) and validation(20%)
4. Training and testing (Architecture1.ipynb)- Implementation of CNN architecture, perform training and evaluate accuracy on testing data
5. Documentation (IMDB_WIKI.pdf)

