# Skin Lesion Classifier

This is my first *real* project in Machine Learning that I've been meaning to complete.

The aim was to create a model able to classify various skin lesions based on photos taken with a smartphone. It's a topic that interests me because of my chronic condition :/

This is only the first iteration; I have many ideas on how to improve and develop the concept further as I learn more and more :)

It probably behoves me to emphasize that I'm not a doctor, have next to no idea about dermatology and the created tool is just a toy and not a substitute for a real diagnosis.

## Overview
The model is a fine-tuned EfficientNet_B0 from PyTorch.

The dataset I used to fine-tune the model comes from [This Dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T) - Thank you Harvard!

It consists of ~10000 train and ~1500 test images of skin lesions separated into 7 different classes.

The classifier notebook contains all the code used to create and train the model. The client notebook is my attempt at creating an interface I can share with others. I certainly want to learn more about HTML, CSS and start learning Javascript to be able to create a simple website for the model

## The client
Just a simple, sherable notebook where the user can drag and drop some smartphone images of their moles, run them through the model and get a classification.
