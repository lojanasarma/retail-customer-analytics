# 2026-Y2-S1-KU-01 - Progress Review I: Data Preprocessing and EDA

## 📖 Project Overview
This repository contains the Data Preprocessing and Exploratory Data Analysis (EDA) pipeline for an E-commerce Customer Segmentation project. 

## 🗄️ Assigned Dataset Details
* **Dataset:** Online Retail II
* **Source:** UCI Machine Learning Repository
* **Location:** `data/raw/online+retail+ii.zip`
* **Description:** Contains over 1 million real-world UK transactional records spanning from 2009 to 2011.

## 👨‍💻 Group Member Roles (Individual Contributions)
* **IT25100020 Nayanajith K.A.T** - Handling missing data & filtering anomalies (Returns).
* **IT25100117 Herath H.M.A.R.B** - Feature engineering (Constructing the RFM matrix).
* **IT24104390 Ahamed M.N.A** - Outlier removal (Using IQR to mathematical remove wholesale outliers).
* **IT25100119 D.D.S.Liyanage** - Encoding categorical variables (One-Hot Encoding for top purchasing countries).
* **IT25100002 Sarma S.S.L** - Normalization / scaling (Log Transformation and StandardScaler).
* **IT23642096 Manathunge A.I** - Feature engineering / Dimension reduction (PCA for 2D visualization).

## 🚀 How to Run the Code
1. Unzip the `online+retail+ii.zip` file located in the `data/raw/` directory so the Excel file is available.
2. Open the `group_pipeline.ipynb` to execute the entire integrated pipeline sequentially.
3. Alternatively, open the individual notebooks in the `notebooks/` folder to view each member's specific preprocessing technique and EDA chart.
4. Outputs will be saved automatically to `results/outputs/` and charts will display inline.
