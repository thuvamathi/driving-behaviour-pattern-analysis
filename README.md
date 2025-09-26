# Driving Behaviour Pattern Analysis in Telematics Data Using K-Means Clustering

This project applies **K-Means Clustering** to telematics data in order to uncover patterns in driving behaviour. By analyzing speed, acceleration, idling, and other factors, drivers are grouped into distinct behavioural clusters. The results provide insights that can be applied in **fleet management, risk assessment, and usage-based insurance**.

---

## 📊 Project Overview
- **Goal**: Identify and interpret distinct driving behaviour patterns from telematics data.  
- **Techniques Used**: Data preprocessing, dimensionality reduction (PCA), clustering (K-Means), and cluster interpretation.  
- **Outcome**: Drivers are segmented into three clusters representing different driving styles:
  - **Cluster 0**: High-speed, efficient but potentially risky drivers.  
  - **Cluster 1**: Low-speed, high-idling, cautious but inefficient drivers.  
  - **Cluster 2**: Balanced drivers with moderate behaviour, reflecting typical urban driving.  

---

## ⚙️ Methodology
1. **Data Preprocessing** – Cleaning and preparing telematics data.  
2. **Exploratory Data Analysis (EDA)** – Identifying patterns and key driving metrics.  
3. **K-Means Clustering** – Optimal cluster count selected using the **Elbow Method** and **Silhouette Score**.  
4. **Dimensionality Reduction (PCA)** – Used to visualize and interpret clusters.  
5. **Cluster Interpretation** – Behavioral insights derived from each group.  

---

## 🛠️ Tech Stack
- **Python**  
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `haversine`  

---

## 📂 Project Structure
