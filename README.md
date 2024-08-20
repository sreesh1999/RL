# RL
Reinforcement Learning for Sepsis Treatment
# Sepsis Treatment Optimization using Reinforcement Learning

## Description
This repository contains the code for optimizing sepsis treatment using reinforcement learning algorithms (DDQN and DDPG). The code was developed and tested using Google Colab.

## How to Run the Code

1. **Google Colab Environment**  
   The code is designed to run in a Google Colab environment. If you intend to run it locally, modifications may be required.

2. **Upload Dataset to Google Drive**  
   - You need to upload the dataset to your Google Drive.
   - Make sure to note the path of the dataset in your Drive.

3. **Mount Google Drive in Colab**
   - The code requires the dataset to be accessed from your Google Drive.
   - To mount your Google Drive in Google Colab, add the following code at the beginning of your notebook:

   ```python
   from google.colab import drive
   drive.mount('/content/drive')

4. **Update Dataset Path in the Code**
   - Locate the section of the code where the dataset path is specified.
   - Change the dataset path to point to the location of the dataset in your Google Drive. For example, if your dataset is located in `MyDrive/datasets/my_dataset.csv`, update the path accordingly:

     ```python
     dataset_path = '/content/drive/MyDrive/datasets/my_dataset.csv'
     ```
