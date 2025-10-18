Technologies Used
- **Language:** Python (latest stable version)  
- **Libraries:**  
  - `Pandas`, `NumPy` → data preprocessing  
  - `Scikit-learn` → IsolationForest, scaling tools  
  - `Matplotlib`, `Seaborn`, `Plotly` → visualization  
- **Environment:** Jupyter Notebook

Anomaly Detection with Z-Score- 
**Steps:**
1. Load dataset and handle missing values  
2. Compute Z-score for each data point  
3. Classify anomalies (|Z| > threshold)  
4. Visualize the time series with anomalies highlighted

Anomaly Detection with Isolation Forest
**Steps:**
1. Clean and normalize dataset  
2. Apply IsolationForest (`Scikit-learn`)  
3. Set contamination rate (e.g., 5%)  
4. Visualize anomalies on the time series

 Non-Functional Requirements
- **Reproducibility:** Fix random seeds, document thresholds and parameters  
- **Visualization Quality:** Clear labels, legends, and titles  
- **Code Quality:** Modular functions and inline comments  
- **Performance:** Efficient vectorized operations where possible 
