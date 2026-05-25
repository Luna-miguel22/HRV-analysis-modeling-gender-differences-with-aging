# HRV Analysis: Modeling Gender Differences with Aging

## End-of-Degree Project

This repository contains the complete workflow developed for the End-of-Degree Project focused on the study of **gender differences in Heart Rate Variability (HRV) across aging**. The project combines signal preprocessing, extraction of linear and non-linear HRV metrics, statistical analysis, dimensionality reduction techniques, and the study of physiological and lifestyle factors influencing HRV.

The notebooks included in this repository are organized according to the different stages of the analysis pipeline.

---

# Repository Structure

## `TFG-preprocessing.ipynb`

Data cleaning and preprocessing pipeline.

Main tasks:

* Signal preparation and filtering
* Extraction of NN intervals
* Artifact correction and handling
* Welch method implementation for spectral preprocessing
* Preparation of datasets for HRV analysis

---

## `TFG-HRV_linear.ipynb`

Extraction and analysis of **linear HRV metrics**.

Included analyses:

* Time-domain HRV metrics
* Frequency-domain HRV metrics


---

## `TFG-HRV_nonlinear.ipynb`

Extraction and analysis of **non-linear HRV metrics**.

* Poincaré plot descriptors
* Entropy-based metrics
* Detrended fluctuation

---

## `TFG-Statistic_General.ipynb`

General statistical analysis of the complete dataset.

Methods included:

* Kruskal–Wallis tests
* Mann–Whitney U tests
* Group comparisons
* Violin plot visualizations
* Distribution analysis of HRV metrics

---

## `TFG-Statistic_Specific.ipynb`

Focused statistical analysis for specific population groups of interest.

This notebook provides:

* Targeted subgroup comparisons
* Detailed statistical evaluation
* Visualization of selected HRV variables
* Analysis of age and gender interactions

---

## `TFG-UMAP.ipynb`

Implementation of **UMAP (Uniform Manifold Approximation and Projection)** for dimensionality reduction and data visualization.

Objectives:

* Visualization of high-dimensional HRV data
* Identification of clusters and hidden patterns
* Exploration of age- and gender-related group separations

---

## `TFG-heart_rate_hrv.ipynb`

Analysis of the relationship between **Heart Rate (HR)** and **Heart Rate Variability (HRV)**.

Included analyses:

* Influence of HR on HRV metrics

---

## `TFG-physical_activity.ipynb`

Analysis of physical activity and body composition variables in relation to HRV.

Included variables:

* Exercise hours
* Body Mass Index (BMI)
* Associations between lifestyle factors and HRV metrics
* Statistical comparisons between activity groups, age and genders

---

## `TFG-Dataset.ipynb`

Dataset exploration and visualization notebook.

Main features:

* Dataset overview
* Demographic visualization
* Summary statistics and plots

---

# Project Objectives

The main objective of this project is to study how **aging affects Heart Rate Variability differently in men and women** using signal processing, statistical analysis, and machine learning techniques.

Specific goals include:

* Extracting and comparing HRV metrics across age and gender groups
* Studying linear and non-linear HRV behavior
* Evaluating the influence of heart rate and physical activity
* Applying dimensionality reduction methods for pattern discovery
* Identifying physiological differences associated with aging

---

# Technologies and Libraries

The project was developed in **Python** using Jupyter Notebooks.

Main libraries used:

* NumPy
* Pandas
* SciPy
* Matplotlib
* Seaborn
* Scikit-learn
* UMAP-learn
* NeuroKit2
* PyHRV

---

# Author: Luna Miguel Mendoza

End-of-Degree Project in Biomedical Engineering.

Topic: **Modeling Gender Differences in Heart Rate Variability with Aging**
