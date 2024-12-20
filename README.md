# MIMIC-CheXpert-Synthetic-Fairness-in-Chest-X-Ray-AI-with-Stable-Diffusion
Enhancing Fairness in Chest X-Ray Diagnostics with Synthetic Data


# 📊 Bridging the Fairness Gap in Medical Imaging Classification

Welcome to the repository! 🎉 This project is part of a **course research project** titled **Bridging the Fairness Gap in Medical Imaging Classification**, conducted under the supervision of **Dr. Laleh Seyyed Kalantari**. Below is an overview of the repository and the critical insights behind this research.

---

## 🌟 Project Overview

This research focuses on **addressing fairness in chest X-ray classification** for Black and White patients, a crucial step towards equitable healthcare diagnostics.

### 📌 Key Research Goals:

1. Reduce **bias** in AI models that diagnose life-threatening diseases like **Cardiomegaly** (enlarged heart muscle) and others.
2. Leverage **DenseNet-121**, a CNN model, customized for chest X-ray analysis.
3. Experiment with **real-world datasets** (like MIMIC-CXR and CheXpert) and **synthetic data** to enhance performance and fairness.
4. Perform **fairness analysis** by evaluating the **False Positive Rate (FPR)** gaps between Black and White patients, especially for the critical "No Finding" label.

---

## 📂 Repository Structure

### 📝 Draft Notebooks Folder

- 🛠️ **Work in Progress**: These are **draft versions** of the project notebooks, serving as initial explorations of the datasets and methods.
  - ⚠️ **Important Note**: These drafts might not be perfectly coded, and **I am actively working on cleaning and refining the code** for better readability and functionality.
- 🛠️ **Detailed Workflow**: You can dive into the **`## Debug`** sections of these notebooks to understand:
  - Dataset modifications 🗂️
  - Preprocessing and sampling for training 🔄
  - Results curation and visualizations 📈
- While these notebooks provide detailed insights, they are best suited for those who wish to understand the **development process**.

### 📋 Final Analysis Files

1. **`FINAL_ANALYSIS_PREP.ipynb`**:
   - 🚀 Simplified experience for curating datasets, preparing JSON outputs, and organizing results.
2. **`FINAL_ANALYSIS.ipynb`**:
   - 🎯 Uses JSON outputs to analyze experiments, visualize findings, and interpret results.

### ⚙️ Config Folder

- The **`config`** folder contains all the **configuration files** for the experiments conducted in this project.
- Each configuration file outlines:
  - **Training methods** and the parameters used for specific experiments.
  - Details about the **training datasets**, including real and synthetic data.
  - Information on **testing and validation datasets** for performance evaluation.
- This setup ensures reproducibility, allowing anyone to replicate or adjust the experiments with ease.

---

## 🛠️ How to Use

### 🧠 Detailed Process Exploration
1. Explore the **Draft Notebooks Folder** for in-depth insights into:
   - ⚙️ Dataset modifications and preprocessing.
   - 📊 Sampling strategies and training pipelines.
   - 🎨 Result visualizations and debugging.

### 🚀 Simplified Workflow
1. Open **`FINAL_ANALYSIS_PREP.ipynb`**:
   - Curate data and prepare JSON output files.
2. Use JSON files with **`FINAL_ANALYSIS.ipynb`**:
   - Analyze experiments.
   - Visualize and interpret results.

---

## 🗂️ Datasets Used

This project uses the following datasets for training and evaluation:
- **MIMIC-CXR**: A large, diverse dataset with real-world metadata for robustness.
- **CheXpert**: A high-quality labeled dataset known for its accuracy.
- **Synthetic Data**: Generated from MIMIC-CXR using **Stable Diffusion** to complement real-world data.

⚠️ **Important Note**: Due to **privacy and access restrictions**, the datasets used in this research (MIMIC-CXR, CheXpert, and the synthetic data) are **not provided in this repository**.  
- Access to MIMIC-CXR and CheXpert requires individual registration and adherence to their respective licensing and usage agreements.
- Synthetic data is derived from MIMIC-CXR and cannot be shared due to ethical considerations.

---

## 📊 Results Highlights

### Key Findings:

- **MIMIC + Synthetic 25%** showed the **best balance of fairness and FPR**, proving that synthetic data can complement real-world datasets effectively.
- **In-domain training** consistently outperformed **out-of-domain approaches**, emphasizing the importance of context-specific data alignment.

---

## 🌍 Significance of the Research

This work demonstrates that **targeted synthetic data strategies** can address representation gaps and improve fairness in AI diagnostics, reducing disparities in healthcare outcomes.

### Practical Implications:
- By mitigating bias in chest X-ray diagnostics, this research helps create AI tools that are **equitable** for all patient groups.
- The findings underscore the importance of **context-aware data strategies** in improving healthcare AI.

---

## 🤝 Thank you for exploring this repository! 🙌 

🎉 **Happy analyzing and visualizing!**

