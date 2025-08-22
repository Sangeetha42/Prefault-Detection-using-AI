# Machine Learning-Based Pre-Fault Detection in Solar PV Systems  

##  Overview  
This project aims to **predict and classify faults in solar photovoltaic (PV) systems** before they occur, improving reliability and reducing downtime.  
A **Random Forest classifier** is used to classify the system state into:  
-  **Normal (Class 0)**  
-  **Pre-Fault (Class 1)**  
-  **Fault (Class 2)**  

---

##  Dataset  
- Collected parameters from solar PV panels:  
  - **IR (Irradiance)**  
  - **Vdcmean1 (Voltage)**  
  - **I1, I2 (Current)**  
  - **T (Temperature)**  
- Data is labeled into **Normal, Pre-Fault, Fault** classes based on thresholds.  
- Format: CSV files (`train_data.csv`, `test_data.csv`)  

---

##  Features  
- Data Preprocessing (handling missing values, cleaning)  
- Train-Test Split for model validation  
- Random Forest Classifier for fault detection  
- Accuracy and Classification Report for model evaluation  
- Visualization of results (bar charts for class distribution)  
- Export predictions to CSV  

---

##  Tech Stack  
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib  
- **Algorithm:** Random Forest Classifier  

---

##  Project Structure  
```
📁 Solar-Fault-Detection
│── 📄 train_data.csv
│── 📄 test_data.csv
│── 📄 aipro1.py          # Main Python script
│── 📄 predicted_results.csv
│── 📄 README.md          # Project Documentation
```

##  Results  
- **Validation Accuracy:** ~ (depends on your data)  
- **Classification Report** generated for evaluation  
- **Visualizations:**  
  - Fault vs No-Fault distribution  
  - Class-wise prediction distribution  

---

##  Future Enhancements  
- Integrate with IoT sensors for real-time monitoring  
- Deploy as a web dashboard (Flask/Django + Chart.js)  
- Extend dataset with real-world solar PV fault logs  

---

