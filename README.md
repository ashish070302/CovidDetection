# CovidDetection using X-ray images

The repository contains folder **Dataset** which contains 2 folder namely "Covid" containing 192 X-ray images of chest scans which are infected with COVID-19 and another folder "Normal" containing 192 X-ray images of chest scans which are not infected by COVID-19.

The other folder **CovidDataset** which contains 2 folder namely "Train" and "Val" both containing again 2 folders "Covid" and "Normal" which is basically a divison of the original Dataset for Train and test purpose.

The file "Dataset_Creator" is used to seperately download and create a seperate folder for creating the dataset as the original dataset is taken from 2 different sources.
The Normal images is taken from a kaggle dataset. Link: "https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia/"
and positive result images from a GitHub repository. Link: "https://github.com/ieee8023/covid-chestxray-dataset".

The file **CovidDetection.ipynb** is the main file was created in Google Collab because of the large size of the dataset and the dataset "CovidDataset" was uploaded to the G-Drive for ease of use in the collab file.
