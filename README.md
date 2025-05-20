# google-AutoML

Image Classification with Google AutoML

This repository documents the process of using Google AutoML to create and train a model for image classification, followed by performing inference using the trained model with TensorFlow 1.x. The goal is to classify images based on a trained AutoML model, with the provided script handling the inference step.

Overview

This project outlines:
* Setting up a dataset and training an image classification model using Google AutoML.
* Exporting the trained model as a TensorFlow .pb file.
* Running inference on new images using the provided Python script with TensorFlow 1.x.

Prerequisites
Before starting, ensure you have the following:
* Google Cloud Account: Access to Google Cloud Platform (GCP) with AutoML Vision enabled.
* Python Environment: Python 3.x with TensorFlow 1.x installed (tensorflow==1.15 recommended).
* Google Cloud Storage: A bucket to store your dataset and exported model.
* Images for Classification: A folder containing images for inference (e.g., .jpg or .png format).
* Google AutoML Setup:
  * A trained AutoML Vision model.
  * The exported .pb model file from AutoML, stored in a local or cloud directory.
