# Intent_detection


This repository contains two notebooks for training and predicting intents:

## 1. Training the Model
The training code and results are available in the `Intent_Detection_Results.ipynb` notebook.  
- **Platform:** It was run on Google Colab using a T4 GPU.  
- **Purpose:** This notebook is provided for display purposes only, showcasing the training code and results.  
- **Note:** There is no need to run this file for predictions as the trained model has been uploaded to Hugging Face.

## 2. Predicting Intent for New Sentences
To predict the intent using the trained model:
- Run the `Intent_Detection_Predict_New.ipynb` notebook.  
- This notebook uses the model uploaded to Hugging Face, eliminating the need to retrain the model.  
- Update the **PDF file path** in the notebook to point to your file.
- Make sure the pdf is the same softmattress_train.csv , as I use it to get the labels.

## Dependencies
Ensure the following libraries are installed before running the notebooks:
- `pandas`
- `transformers`
- `sklearn`
- `torch`

## Installation Instructions
Use the following bash commands to install the dependencies:

```bash
# Install required libraries
pip install pandas transformers scikit-learn torch
