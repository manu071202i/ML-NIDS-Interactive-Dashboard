# Machine Learning-based Network Intrusion Detection (ML-NIDS) Interactive Dashboard

## Project Overview
This project presents an interactive web dashboard designed to showcase a Machine Learning-based Intrusion Detection System (ML-NIDS). It provides an in-depth look into the dataset, the machine learning pipeline, model performance comparisons, and actionable insights derived from intrusion detection.

**Goal:** To enhance intrusion detection systems' precision and dependability, shield networks from online dangers, conduct a comparative analysis of several machine learning models and feature selection strategies, and assist businesses in finding errors and issues with the setups of their network devices.

## Features
* **Interactive Dataset Overview:** Visualizes the distribution of different attack categories within the UNSW-NB15 dataset.
* **ML Pipeline Visualization:** A clear, step-by-step representation of the data processing and model training workflow.
* **Dynamic Model Performance Comparison:** Select from various machine learning models (Logistic Regression, Decision Tree, Random Forest, SVM, MLPClassifier, XGBoost) to compare their F1-Score, Accuracy, Precision, and Recall.
* **Feature Importance Visualization:** Understand which network traffic features are most influential for each selected model.
* **Actionable Insights:** Correlates detected intrusion types with common network misconfigurations and vulnerabilities.
* **Responsive Design:** Optimized for seamless viewing across desktop, tablet, and mobile devices.

## Technologies Used
* **Frontend:** HTML5, CSS3 (Tailwind CSS)
* **Interactivity & Data Visualization:** JavaScript (Vanilla JS, Chart.js)
* **Data Source:** UNSW-NB15 Dataset (simulated data for demonstration)

## How to Run This Dashboard (Web Version)
This is a single-page web application. To view it:
1.  Download the `index.html` file to your computer.
2.  Open the `index.html` file using any modern web browser (e.g., Chrome, Firefox, Edge).
3.  Alternatively, you can host it easily using GitHub Pages (see "Live Demo" section below).

## Live Demo
(Once you've uploaded and set up GitHub Pages, you'll put your live link here, e.g., `https://your-username.github.io/your-repository-name/`)
## Setup (for a full Python ML project - conceptual)
If you were to build the full Python backend for this project, you would:
1.  **Clone the repository:**
    `git clone https://github.com/your-username/ML-NIDS-Project.git`
    `cd ML-NIDS-Project`
2.  **Create and activate a virtual environment:**
    `python -m venv venv`
    `source venv/bin/activate` (Linux/macOS) or `.\venv\Scripts\activate` (Windows)
3.  **Install dependencies:**
    `pip install -r requirements.txt`
4.  **Download and place the UNSW-NB15 dataset** into the `data/` directory.
5.  **Run the main script:**
    `python src/main.py`

## Author
Manu Kumar
