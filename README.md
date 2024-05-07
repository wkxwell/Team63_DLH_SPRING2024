# Team63_DLH_SPRING2024
VIDEO DEMO LINK:

--ENVIRONMENT--

PACKAGE NEEDED TO COMPILE THE CODE: PYTHON 3.7

--PACKAGES-- pandas for data manipulation, matplotlib for the graphs scikit-learn for DL


import numpy as np
from google.colab import drive
import tensorflow as tf
import pandas as pd

Data
The data we used in this research project is coming from the MIMIC III Health datasets which aligns with the research paper. The research paper used this dataset as a cross validation. However due to certain data being unavailble as the original dataset were from NYU CUIMC which we are unable to retrieve. Certain modifications are done to the dataset to make the usable in our context.

The dataset includes patient demographics from the PATIENTS table and clincial measurements from the CHARTEVENTS table. Typical visualizations include histograms of patient age and gender distribution, and time series plots of clinical measurements.

Data was preprocessed using a script that filters patients based on ids, ages, etc. in the master.csv
