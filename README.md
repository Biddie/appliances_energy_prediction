# appliances Energy Prediction

## Introduction

This repo is for Appliances Energy Predictions

## Environment Setup

If your conda base environment is old, it is important that you install the setuptoolsand wheel packages that are dependencies for autogluon.

pip install setuptools wheel

Step 1: Create Environment
conda create --name appEnergy python=3.9 -y

Step 2. Activate Environment
conda activate applianceenv

Step 3. Install required packages
pip install torch==1.12.1+cpu torchvision==0.13.1+cpu torchtext==0.13.1 -f https://download.pytorch.org/whl/cpu/torch_stable.html
pip install autogluon streamlit jupyter

## Code Structure

## Exploratory Data Analysis (EDA)

## Model Building 

## Model Evaluation

## Model WebApp (Streamlit)