<h1>Chronic Kidney Disease (CKD) Detection</h1>

This project is a machine learning-based system designed to predict Chronic Kidney Disease (CKD) using patient health data. <br>
It features a Streamlit web application where users can input medical parameters and receive real-time predictions.
---
<h2>Project Structure</h2>

CKD_Model_Training_Updated.ipynb'             '# Jupyter Notebook for model training<br>
kidney_disease.csv'                           '# Dataset used for training<br>
ckd_model.pkl'                                '# Trained Random Forest model<br>
ckd_predictor_app.py'                         '# Streamlit web application<br>
README.md'                                     '# Project documentation<br>

---
<h2>Features</h2>
* Uses Random Forest Classifier for CKD detection.<br>
* Web-based interface built with Streamlit.<br>
* Accepts user inputs for medical parameters (e.g., blood pressure, hemoglobin, sugar levels).<br>
* Provides instant CKD prediction results.<br>
---
<h2>Tech Stack</h2>

* Python 3<br>
* Pandas, NumPy, Scikit-learn<br>
* Streamlit<br>
* Pickle (for model serialization)<br>

---
<h2>Dataset</h2>

The dataset `kidney_disease.csv` contains patient information including:

* Age, Blood Pressure, Specific Gravity, Albumin, Sugar
* Blood Glucose Random, Blood Urea, Serum Creatinine
* Hemoglobin, Sodium, Potassium, and other medical parameters.

---

## **How to Run the Project**

### **1. Clone the repository**

```bash
git clone https://github.com/your-username/ckd-detection.git
cd ckd-detection
```

### **2. Install dependencies**

```bash
pip install -r requirements.txt
```

### **3. Run the Streamlit app**

```bash
streamlit run ckd_predictor_app.py
```

---

## **Usage**

* Open the Streamlit app in your browser.
* Input patient details into the form.
* Click **Detect** to check the CKD prediction.

---

## **Model Training**

* The model is trained using a **Random Forest Classifier** in the `CKD_Model_Training_Updated.ipynb` notebook.
* Preprocessing steps include handling missing values, encoding categorical variables, and scaling numerical features.

---

## **Future Enhancements**

* Improve model accuracy with hyperparameter tuning.
* Deploy the web app using **Streamlit Cloud / AWS / Heroku**.
* Add data visualization for CKD trends.

---

## **License**

This project is open-source and available under the [MIT License](LICENSE).

