# Satellite-Imagery-Based-Property-Evaluation

This repository contains the complete implementation of a multimodal machine learning system for predicting house prices using **tabular housing attributes** and **satellite imagery**.  
---

## 📂 Repository Structure
```text
├── data_fetcher.py               # Script to load and prepare satellite images
├── preprocessing.ipynb           # Data cleaning, EDA, and feature engineering
├── model_training.ipynb          # Model training (Tabular, CNN, Multimodal)
├── 23119050_final.csv            # Final prediction file (id, predicted_price)
├── 23119050_report.pdf           # Final project report (PDF)
├── README.md                     # Project instructions
├── NN1_on_tabular_data.ipynb     # contains tabular only trained neural network (just for reference) 
```

## ⚙️ Environment Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<TavisheeAgrwal>/<Satellite-Imagery-Based-Property-Evaluation>.git
cd <Satellite-Imagery-Based-Property-Evaluation>
```

### 2️⃣ Install Dependencies

It is recommended to use Google Colab.
If running locally, install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn torch torchvision xgboost opencv-python
```
## How to Run the Project
# Step 1: Data Preprocessing & EDA

Open and run:

preprocessing.ipynb


This notebook:

Loads the CSV datasets

Performs EDA and visualization

Cleans data and creates engineered features

Saves processed datasets
