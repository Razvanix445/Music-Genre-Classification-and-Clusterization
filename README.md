# Music Genre Classification and Clustering

Machine Learning project implementing k-NN and k-Means algorithms on the GTZAN music dataset for genre classification and clustering.

## 📋 Project Overview

This project performs:
- **Data Analysis** of GTZAN music genre dataset
- **Classification** using k-Nearest Neighbors (k-NN)
- **Clustering** using k-Means algorithm

## 👥 Team Members

- Călăuz Răzvan
- Creț Larisa

**Course:** Machine Learning  
**Institution:** Babeș-Bolyai University  
**Date:** November 2025

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook
- Kaggle account (for dataset download)

### Step 1: Clone the Repository
```bash
git clone https://github.com/Razvanix445/Music-Genre-Classification-and-Clusterization.git
cd Music-Genre-Classification-and-Clusterization
```

### Step 2: Install Required Packages
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn kaggle jupyter
```

### Step 3: Set Up Kaggle Credentials

#### 3.1 Create a Kaggle Account

#### 3.2 Get Your API Token

#### 3.3 Place the Token in the Correct Location

```bash
mkdir %USERPROFILE%\.kaggle
move %USERPROFILE%\Downloads\kaggle.json %USERPROFILE%\.kaggle\
```

---

## 📊 Running the Analysis

### Run Jupyter Notebook
```bash
cd data_analysis
jupyter notebook gtzan_analysis.ipynb
```

---

## 💾 Dataset Information

### GTZAN Music Genre Dataset

- **Source:** [Kaggle - GTZAN Dataset](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)
- **Size:** ~1.2 GB
- **Samples:** 1000 audio files
- **Genres:** 10 (blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, rock)
- **Features:** 57 audio features extracted from 30-second clips

### Dataset Download

The notebook will **automatically download** the dataset to `~/dataset/gtzan/` on first run.

**Location:** The dataset is stored in this directory:
- **Windows:** `C:\Users\your-username\dataset\gtzan\`

**Note:** The dataset is NOT included in this repository due to its large size.

---

## 📄 License

This project is for educational purposes as part of the Machine Learning course.

---

**Last Updated:** November 2025