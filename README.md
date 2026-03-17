# Hybrid Experimental–Machine Learning Framework for Graphene-Modified Ultrafiltration Membranes

<img width="756" height="564" alt="image" src="https://github.com/user-attachments/assets/04872447-7356-4451-a4d2-94cb5c905df4" />



---

## Overview

This repository contains the machine learning models, analysis scripts, and interactive prediction interface developed for optimizing graphene-modified ultrafiltration membrane performance in industrial wastewater treatment. The framework predicts permeate concentrations for metal ions, organic pollutants, and inorganic salts based on operating conditions.

---

## Models

| Target | Best Model | Test R² |
|---|---|---|
| Metal ion removal (Y1) | K-Nearest Neighbors | 0.879 |
| Organic pollutant removal (Y2) | XGBoost | 0.998 |
| Salt transport (Y3) | Support Vector Regression | 0.983 |

---

## Repository Structure
```
├── data/               # Experimental dataset (135 filtration runs)
├── models/             # Trained ML models
├── scripts/            # Preprocessing and training scripts
├── interface/          # Web-based prediction interface
└── README.md
```

---

## Usage

Clone the repository and install dependencies:
```bash
git clone https://github.com/montassar-ML/[repo-name].git
cd [repo-name]
pip install -r requirements.txt
```

Launch the prediction interface:
```bash
python app.py
```

The interface accepts CO, CM, CS, and applied pressure P as inputs and returns predicted permeate concentrations.

---

## Live Demo

The deployed prediction interface is available at: **https://github.com/Hassenamri005/montassar**

---



---

## Contact

bouzidimontassar2@gmail.com
