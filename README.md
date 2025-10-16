# Network Anomaly Detection Using LSTM Autoencoder

## Overview

This project implements a network anomaly detection system using an **LSTM Autoencoder** and compares its performance with **One-Class SVM (OC-SVM)** and **Least Squares SVM (LS-SVM)**. The model is trained and evaluated using the [UNSW-NB15 dataset](https://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15), which contains a diverse set of network traffic data, including normal and attack traffic.

## Dataset

The dataset used in this project is the **UNSW-NB15** dataset, available on Kaggle:

- [UNSW-NB15 Dataset](https://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15)

### Dataset Details

- **Source**: The dataset was created by the Australian Centre for Cyber Security (ACCS) and contains 9 types of attacks: Fuzzers, Analysis, Backdoors, DoS, Exploits, Generic, Reconnaissance, Shellcode, and Worms.
- **Format**: CSV files
- **Features**: The dataset includes 49 features, such as protocol type, service, flag, and various statistical measures of traffic.

### Dataset Structure

- `UNSW-NB15_1.csv`: Contains the training data.
- `UNSW-NB15_2.csv`: Contains the testing data.

## Project Structure

