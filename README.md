
# Time Series Analysis: Stress and Affect Detection

## Project Overview

This project focuses on **Stress and Affect Detection** through the analysis of time-series physiological data. It processes multi-modal sensor data to identify and categorize different states of stress and affect.

## Author

  * **Name:** Rian Renold Dbritto
  * **NUID:** 002026598

## Description

The primary goal of this project is to set up a robust pipeline for handling and preparing time-series data for subsequent analysis aimed at detecting stress and affective states. The notebook demonstrates the initial steps of loading, verifying, and transforming raw sensor data into a structured format suitable for machine learning or in-depth signal processing.

## Key Features & Methodology

  * **Data Loading:** Utilizes `pickle` to load pre-processed `.pkl` files containing WESAD (Wearable Stress and Affect Detection) dataset.
  * **Multi-modal Sensor Data:** Handles data from both chest and wrist sensors, including:
      * **Chest:** Accelerometer (ACC), Electrocardiogram (ECG), Electromyography (EMG), Electrodermal Activity (EDA), Temperature (Temp), Respiration (Resp).
      * **Wrist:** Accelerometer (ACC), Blood Volume Pulse (BVP), Electrodermal Activity (EDA), Temperature (TEMP).
  * **Data Verification:** Includes steps to verify the structure, length, and shape of loaded signals and corresponding labels.
  * **Data Transformation:** Converts raw sensor readings and labels into a tabular format using `pandas` DataFrames, making the data easily accessible for further analysis. This involves creating columns for each signal component and adding 'label' and 'subject' identifiers.

## Data Source

The project relies on the **WESAD (Wearable Stress and Affect Detection) Dataset**. The notebook expects the `.pkl` files for subjects (e.g., S2, S4, S6, S8, S10) to be accessible, typically mounted from a Google Drive path.

## Project Files

  * `Time_Series_Analysis (1).ipynb`: The main Jupyter Notebook containing the project's code, data loading, and transformation steps.
  * `WESAD FILES/`: (Expected Directory) This directory should contain the WESAD dataset's `.pkl` files (e.g., `S2.pkl`, `S4.pkl`, etc.).







-----
