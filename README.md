#### **WIND TURBINE POWER GENERATION FORECASTING**   

Overview  
This project focuses on forecasting wind turbine power generation based on various environmental and operational factors. The dataset is sourced from Kaggle and contains records related to wind speed, turbine efficiency, and power output.

The objective is to develop a predictive model using machine learning techniques to estimate wind turbine power generation accurately.

Dataset  
Source: Kaggle - <a href="https://www.kaggle.com/datasets/gauravduttakiit/wind-turbine-power-generation-forecasting" target="_blank">Wind Turbine Power Generation Forecasting</a>  
Size: Large dataset with multiple features affecting power generation  
Access: The dataset is not included in this repository and must be downloaded using the Kaggle API  

Setting Up the Kaggle API

To download the dataset, you need to authenticate using your **Kaggle API Key**. Follow these steps:
### **1️. Get Your Kaggle API Key**
1. Go to [Kaggle Account](https://www.kaggle.com/account).
2. Scroll down to the **API** section.
3. Click **"Create New API Token"** – this will download a file named `kaggle.json`.
4. Open `kaggle.json` in a text editor and copy your **Kaggle username** and **API key**.

### **2️. Manually Set Your API Key in Code**
Instead of uploading `kaggle.json`, you can enter your credentials directly in the code:

```python
import os

# Replace with your Kaggle API credentials
os.environ["KAGGLE_USERNAME"] = "your_username"
os.environ["KAGGLE_KEY"] = "your_api_key"
