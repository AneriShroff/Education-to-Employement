
# 🎓 Education to Employment: Data Mining for Job Offers and Salary Prediction

![License](https://img.shields.io/badge/license-Academic-blue)
![Python](https://img.shields.io/badge/python-3.8+-brightgreen)
![Status](https://img.shields.io/badge/status-Completed-success)

This repository provides all resources for the MSc Thesis **"Education to Employment: Data Mining for Job Offers and Salary Prediction"** by Shroff Aneri Vipulkumar.  
The project explores how academic records, certifications, and networking contribute to predicting:
- 🎯 **Number of Job Offers** (Classification)
- 💰 **Starting Salary** (Regression)

## ✨ Key Features
- Fully reproducible Machine Learning pipelines for classification and regression.
- Model explainability using SHAP (SHapley Additive exPlanations).
- Performance evaluation with metrics like Accuracy, ROC-AUC, MAE, and RMSE.
- Clean, structured, and well-documented Python Jupyter Notebooks.

---

## 🗂️ Repository Structure

```'

📦 Education-to-Employment
┣ 📁 data/                             # Dataset (Not included due to privacy)
┣ 📁 models/                           # Saved trained models (Optional)
┣ 📁 notebooks/                        # Jupyter Notebooks for all steps
┃ ┣ 📄 01\_Data\_Preprocessing.ipynb     # Data cleaning and preparation
┃ ┣ 📄 02\_Model\_Training\_Regression.ipynb # Salary prediction model
┃ ┣ 📄 03\_Model\_Training\_Classification.ipynb # Job offers prediction model
┃ ┗ 📄 04\_Model\_Interpretability\_SHAP.ipynb   # SHAP explainability analysis
┣ 📄 requirements.txt                  # List of required Python packages
┣ 📄 README.md                         # Project documentation (this file)
┗ 📄 Thesis\_Project\_Report.pdf         # Final thesis report document

````

---

## How to Reproduce Results

### 1. Clone the Repository
```bash
git clone <your-repository-url>
cd Education-to-Employment
````

### 2. Set Up the Environment on Windows: venv\Scripts\activate

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### 3. Run the Notebooks in Sequence

1. `notebooks/01_Data_Preprocessing.ipynb`
2. `notebooks/02_Model_Training_Regression.ipynb`
3. `notebooks/03_Model_Training_Classification.ipynb`
4. `notebooks/04_Model_Interpretability_SHAP.ipynb`

Run them using **Jupyter Notebook** or **Google Colab**.

---

## Dependencies

* Python 3.8+
* pandas
* numpy
* scikit-learn
* xgboost
* lightgbm
* imbalanced-learn
* shap
* matplotlib
* seaborn

Install all dependencies with:

```bash
pip install -r requirements.txt
```

---

## Key Outputs

* **Model Performance Metrics**

  * Classification: Accuracy, F1-Score, ROC-AUC
  * Regression: MAE, RMSE, R²

* **SHAP Visualizations**

  * Summary plots, Beeswarm plots, Bar charts

* **Confusion Matrix and Error Distributions**

---

## Documentation

* `Thesis_Project_Report.pdf`: Comprehensive thesis report covering objectives, methods, experiments, and findings.

---

## Example Usage

After running the notebooks, you will obtain:

* Salary prediction error metrics.
* Classification performance for job offers.
* Visual SHAP plots explaining model decisions.

---

## Future Work

* Adding behavioral and socio-economic data.
* Testing deep learning-based models for improved predictions.
* Building a web application for real-time prediction services.

---

## Author

Shroff Aneri Vipulkumar
MSc IT for Business Data Analytics
International Business School
May 2025

---

## Contributing

Contributions are welcome.
Fork the repository, make your changes, and submit a pull request.

---

## Issue Reporting

If you encounter any bugs or have feature suggestions,
please open an issue on the **GitHub Issues Tab** of this repository.

---

## License

This project is provided **for academic and educational purposes only**.
Contact the author for permission if you wish to use it in any other context.

---

## Ready to Explore

Clone, run and discover how data mining can predict graduate employability outcomes!
