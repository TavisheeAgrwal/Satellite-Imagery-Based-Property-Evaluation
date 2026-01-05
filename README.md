# Satellite-Imagery-Based-Property-Evaluation

This repository contains the complete implementation of a multimodal machine learning system for predicting house prices using **tabular housing attributes** and **satellite imagery**.  
---

## 📂 Repository Structure
```text
├── data_fetcher.py               # Script to load and prepare satellite images
├── preprocessing.ipynb           # Data cleaning, EDA, and feature engineering and baseline prediction
├── model_training.ipynb          # Model training (Multimodal)
├── 23119050_final.csv            # Final prediction file (id, predicted_price)
├── 23119050_report.pdf           # Final project report (PDF)
├── README.md                     # Project instructions
├── NN1_on_tabular_data.ipynb     # contains tabular only trained neural network (just for reference) 
```
I have provided the prediction file 23119050_final.csv , kindly use it for evaluation purposes.
If you want to run other files by yourself follow the steps.
## ⚙️ Environment Setup

### 1️ Clone the Repository
```bash
git clone https://github.com/<TavisheeAgrwal>/<Satellite-Imagery-Based-Property-Evaluation>.git
cd <Satellite-Imagery-Based-Property-Evaluation>
```

### 2️ Install Dependencies

It is recommended to use Google Colab.
If running locally, install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn torch torchvision xgboost opencv-python
```
## 3 Run files
### Run data_fetcher.py
Kindly generate your mapbox API key and replace it in the code and import the images in your folder.
I have imported the images in two folders and then later on combined those folders into one for easy coding later on.
### Run preprocessing.ipynb
It will perform eda , viaualization , preprocessing , feature engineering , add image paths and store it in csv formats and also perform baseline model training on tabular only data.
### Run model_training.ipynb
This will train the model and general predictions and accuracy scores like R2 and RMSE.
