# 🛡️ ML-NIDS: Machine Learning-Based Network Intrusion Detection Dashboard

An interactive web-based dashboard that showcases a Machine Learning-powered Intrusion Detection System (IDS) using the UNSW-NB15 dataset. This project provides insight into the data, compares multiple ML models, visualizes key features, and highlights actionable insights into network vulnerabilities and misconfigurations.

---

## 🎯 Project Goals

- Enhance the precision and reliability of intrusion detection systems.
- Protect networks from cyber threats by leveraging ML techniques.
- Compare the effectiveness of multiple machine learning algorithms.
- Visualize the impact of feature selection on model performance.
- Provide organizations with insights into network vulnerabilities.

---

## 🚀 Features

- 📁 **Interactive Dataset Overview**  
  Visualize the distribution of different attack categories from the UNSW-NB15 dataset.

- 🔄 **ML Pipeline Visualization**  
  Step-by-step representation of the data preprocessing and model training flow.

- 📊 **Model Performance Comparison**  
  Select and compare models (Logistic Regression, Decision Tree, Random Forest, SVM, MLPClassifier, XGBoost) using metrics like F1-Score, Accuracy, Precision, and Recall.

- 📌 **Feature Importance Visualization**  
  Discover which network traffic features have the most influence on detection.

- 💡 **Actionable Insights**  
  Links intrusion types to likely misconfigurations or vulnerabilities in the system.

- 📱 **Responsive Design**  
  Optimized for use on desktops, tablets, and mobile devices.

---

## 🧰 Tech Stack

| Layer       | Technology                |
|-------------|----------------------------|
| Frontend    | HTML5, CSS3 (Tailwind CSS) |
| Interactivity & Charts | Vanilla JS, Chart.js        |
| Dataset     | UNSW-NB15 (simulated for demo) |

---

## 📂 How to Run (Web Version)

> This is a single-page application (SPA).

1. **Download** or **clone** the repository.
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge).
3. ✅ You're done!

### Optional: Host with GitHub Pages

1. Push the repo to GitHub.
2. Go to **Settings > Pages**.
3. Choose the `main` branch as the source.
4. Your site will be live at `https://your-username.github.io/your-repo-name/`.

---

## 🐍 (Optional) Python Backend Setup – Conceptual ML Pipeline

If you'd like to integrate or run the full ML backend (model training, data processing):

```bash
# Clone the repo
git clone https://github.com/your-username/ML-NIDS-Project.git
cd ML-NIDS-Project

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # For macOS/Linux
# OR
.\venv\Scripts\activate    # For Windows

# Install dependencies
pip install -r requirements.txt

# Add the UNSW-NB15 dataset
# Place dataset files into the `data/` directory

# Run the main script
python src/main.py
