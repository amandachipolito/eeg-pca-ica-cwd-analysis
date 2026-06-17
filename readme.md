# EEG Analysis Using PCA, ICA and Choi-Williams Distribution

Academic project developed during the Biomedical Signal Processing course at the Federal University of ABC (UFABC).

---

## Overview

This project investigates the application of Principal Component Analysis (PCA), Independent Component Analysis (ICA), and Choi-Williams Distribution (CWD) for the analysis of epileptic EEG recordings.

The study was conducted using seven seizure events from patient CHB1 of the CHB-MIT Scalp EEG Database.

The objective was to evaluate how dimensionality reduction, source separation, and time-frequency analysis can reveal relevant structures associated with epileptic seizures.

---

## Objectives

* Analyze epileptic EEG signals.
* Investigate inter-channel synchronization during seizures.
* Identify candidate ictal components using ICA.
* Characterize seizure activity in the time-frequency domain.
* Explore computational biomarkers for seizure detection.

---

## Methods

### Preprocessing

* Band-pass filtering (1–30 Hz)
* Signal normalization
* Covariance analysis

### Dimensionality Reduction

* Principal Component Analysis (PCA)

### Source Separation

* Independent Component Analysis (ICA)

### Time-Frequency Analysis

* Choi-Williams Distribution (CWD)

### Statistical Analysis

* Band-power comparison
* Kurtosis analysis
* Signal-to-Noise Ratio (SNR)
* Sliding-window PCA

---

## Dataset

**CHB-MIT Scalp EEG Database**

Patient analyzed:

* CHB1

Number of seizures analyzed:

* 7

---

## Main Results

* Increased synchronization during ictal periods.
* Concentration of variance in the first principal components.
* Identification of candidate ictal components.
* Mean ictal rhythmic power of 67.8%.
* Mean reconstruction SNR of 11.7 dB.
* Potential seizure biomarker based on PCA eigenvalue dynamics.

---

## Techniques and Concepts

* Electroencephalography (EEG)
* Biomedical Signal Processing
* Principal Component Analysis (PCA)
* Independent Component Analysis (ICA)
* Time-Frequency Analysis
* Choi-Williams Distribution (CWD)
* Seizure Detection
* Computational Neuroscience

---

## Authors

Amanda Cruz Hipólito

Fernando Sanchez

Vinícius Zacheo de Goes

---

## Full Article

📄 Read the complete manuscript:

[Application of PCA, ICA and CWD in the Analysis of Epileptic EEG](https://github.com/amandachipolito/eeg-pca-ica-cwd-analysis/blob/main/paper/Application%20of%20PCA%20ICA%20and%20CWD%20in%20the%20Analysis%20of%20Epileptic%20EEG%20-%20A%20Study%20with%20Seven%20Seizures%20from%20Patient%20CHB1.pdf)

---

## Academic Context

This repository contains an academic project developed during the Biomedical Signal Processing course and is intended for educational and research purposes.
