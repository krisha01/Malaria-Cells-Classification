# Malaria-Cells-Classification


The primary purpose of this notebook is to perform Image classification from a public dataset called Malaria Cell Images Dataset that has more than 27,500 images of malaria cells of 2 categories - Parasitized and Uninfected cells. To perform our image classification, we use a Convolutional Neural network after preprocessing the image data to generate accurate results. The dataset contains 27,558 images of blood smear slide images. The data collection is based on the data from National Institute of Health - National Library of medicine (https://lhncbc.nlm.nih.gov/publication/pub9932). The pictures are divided into 2 classes: Parasitized and Uninfected. For each class there are about 13,800 images. Images are not high resolution. The baseline Convolutional Neural Network model gave us an accuracy of 96.081% with 20 epochs. The baseline model was trained without preprocessing the images with the ImageDataGenerator class. Another model was trained after preprocessing the images with the ImageDataGenerator class which gave an accuracy of 89.06% after training the CNN model for 50 epochs. When working with neural networks and especially CNN, there are n amount of possibilities to make our model and evaluate its performance. In this notebook, I have demonstrated few of them.

To run the project and load the dataset, follow the below instructions -

•	Download the dataset from - https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria

•	Keep all the files provided and the downloaded dataset in either the current working directory or change the working directory to any path you like in the Jupyter Notebook.

•	Open ‘Malaria Cells Classification.ipynb’ and run it.

•	You will find all the steps from importing the libraries, image preprocessing, network architecture etc for the classification there
