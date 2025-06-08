ML-NIDS: Machine Learning-Based Network Intrusion Detection Interactive Dashboard
📊 Project Overview
This project delivers an interactive web dashboard showcasing a Machine Learning-based Intrusion Detection System (ML-NIDS). It provides intuitive, visual insight into the dataset, machine learning pipeline, model performance, and actionable security insights.

🎯 Goal
To enhance the precision and reliability of intrusion detection systems, compare machine learning models and feature selection techniques, and support organizations in identifying vulnerabilities and misconfigurations within their networks.

🔧 Features
📁 Interactive Dataset Overview
Visualizes the distribution of attack types in the UNSW-NB15 dataset.

🔄 ML Pipeline Visualization
Step-by-step illustration of data processing, training, and evaluation stages.

📊 Model Performance Comparison
Dynamically compare models (Logistic Regression, Decision Tree, Random Forest, SVM, MLPClassifier, XGBoost) using F1-Score, Accuracy, Precision, and Recall.

📌 Feature Importance Visualization
Displays influential features in network traffic for each model.

📈 Actionable Insights
Connects intrusion types with common system misconfigurations and vulnerabilities.

📱 Responsive Design
Fully responsive layout for desktop, tablet, and mobile devices.

💻 Technologies Used
Frontend: HTML5, CSS3 (Tailwind CSS)

Visualization: Vanilla JavaScript, Chart.js

Data Source: UNSW-NB15 Dataset

🚀 How to Run This Dashboard (Web Version)
Download the index.html file.

Open it in any modern web browser (Chrome, Firefox, Edge).

(Optional) Host it via GitHub Pages for sharing:

bash
Copy
Edit
# GitHub Pages Hosting Instructions:
# Push to your GitHub repo, then go to Settings > Pages > Select main branch
🔬 Conceptual Backend Setup (Python ML Pipeline)
To build and run the Python-based ML backend:

bash
Copy
Edit
# Clone the repo
git clone https://github.com/your-username/ML-NIDS-Project.git
cd ML-NIDS-Project

# Set up environment
python -m venv venv
source venv/bin/activate  # macOS/Linux
# OR
.\venv\Scripts\activate    # Windows

# Install dependencies
pip install -r requirements.txt

# Add the UNSW-NB15 dataset
# Place the dataset into the `data/` directory

# Run the main ML script
python src/main.py
