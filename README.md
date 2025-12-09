# 429 Final Project

## Project Overview
This repository contains the final project for course **DAEN 429**.  
The goal of this project is to train, evaluate, and deploy a machine learning model for ASL alphabet detection.  
It includes the code, notebooks, and saved model weights necessary to reproduce results.

## Repository Structure
- **S-A.ipynb**  
  From scratch custom CNN model using Keras.

- **best_model_weights.zip**  
  Compressed archive of the trained model’s weights.  
  Use this to reload the model without retraining from scratch.  
  (Requires Git LFS since the file is large.)

- **TABC_models.ipynb**  
  Pre-trained ResNet-18 model with differnt heads frozen for experiments

