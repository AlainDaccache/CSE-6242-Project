# CSE-6242-Project - Bike Share Analysis

## Data Collection

Data is from 2016-2020

### Bike Share Data
Download the data from the following link: https://www.kaggle.com/datasets/jeanmidev/public-bike-sharing-in-north-america/data
Unzip the folder, and keep only the Toronto data. 
Move the three CSV files that contain the Toronto data into the `data/raw/` 
folder within root.

### Traffic Data
Download data from https://open.toronto.ca/dataset/traffic-volumes-at-intersections-for-all-modes/
Specifically: locations.csv, count_metadata.csv, raw-data-2010-2019.csv, and raw-data-2020-2029.csv.
Move them under the `data/raw/` folder

## Environment Setup

```
# create environment 'bike-env'
python -m venv bike-env3
# activate environment
bike-env3\Scripts\activate.bat
# install dependencies
python -m pip install -r requirements.txt
# start Jupyter Server
jupyter nbextension enable --py widgetsnbextension
jupyter lab
```
There should be in the output a couple lines as such; please open either to access the lab environment.
```
[I 2024-10-12 13:36:49.160 ServerApp] http://localhost:8888/lab?token=5f512ee4481608b837ccb4c3e937c945e42c06881df6568a
[I 2024-10-12 13:36:49.160 ServerApp]     http://127.0.0.1:8888/lab?token=5f512ee4481608b837ccb4c3e937c945e42c06881df6568a
```
