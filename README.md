# CSE-6242-Project - Bike Share Analysis

Download the data from the following link: https://www.kaggle.com/datasets/jeanmidev/public-bike-sharing-in-north-america/data

Unzip the folder, and keep only the Toronto data. 
Move the three CSV files that contain the Toronto data into the `data/raw/` 
folder within root.


```
# create environment 'bike-env'
python -m venv bike-env
# activate environment
bike-env\Scripts\activate.bat
# install dependencies
python -m pip install -r requirements.txt
# start Jupyter Server
python -m jupyter notebook
```