# Cardiovascular Disease Prediction (MSc Project)

MSc project (University of Salford, 2025).  
Applied machine learning to predict cardiovascular disease using the `cardio_train.csv` dataset (~70,000 patient records).

---

## Methods
- Models: Logistic Regression, Random Forest, XGBoost, CatBoost, Artificial Neural Networks (ANN)  
- Feature Engineering: BMI, Pulse Pressure, Mean Arterial Pressure (MAP), Cholesterol Index, Obesity Flag  
- Hyperparameter Optimisation: RandomizedSearchCV with 10-fold stratified cross-validation  
- Evaluation Metric: Recall (~80% sensitivity on CVD-positive cases), prioritising reduction of false negatives  

---

## Files
- `notebooks/Notebook.ipynb` – main ML workflow  
- `data/cardio_train.csv` – dataset (70,000 records)  
- `requirements.txt` – Python dependencies  

---

## Results
- ANN achieved ~80% recall on CVD-positive cases while maintaining balanced precision  
- Compared baseline and modern classifiers under stratified cross-validation; analysed precision/recall tradeoffs for clinical screening use 
- Methods transferable to healthcare analytics, predictive maintenance, and anomaly detection  

---

## How to Run
1. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

2. Launch Jupyter Notebook:  
   ```bash
   jupyter notebook notebooks/Notebook.ipynb
   ```

3. Run all cells to reproduce preprocessing, model training, and evaluation results.
