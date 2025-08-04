# process-correlation-analysis
correlation works: between simulation and empirical outcomes
---

## 📄 Abstract

This study analyzes the correlation between coating thickness and flow variables in FOWLP chambers. Strong linear relationships were found between average pressure and coating uniformity, especially in hole-type designs. Slit chambers with baffles also showed improved correlation under stable pressure conditions. The results suggest that chamber geometry and flow control are key to process stability.

---

## 📐 Mathematical Method
The wafer film quality was analyzed using Six Sigma statistical indicators as follows:

#### ✅ 1. Pearson Correlation Coefficient
<p align="left"><img width="658" height="305" alt="image" src="https://github.com/user-attachments/assets/11c5a057-121e-4843-9088-d70210a99a70" />
  
#### ✅ 2. t-Statistic for Hypothesis Testing
<p align="left"><img width="658" height="122" alt="image" src="https://github.com/user-attachments/assets/212a9577-b6d9-43fa-96df-10b88fdecab2" />
  
#### ✅ 3. p-Value from t-Distribution
<p align="left"><img width="658" height="75" alt="image" src="https://github.com/user-attachments/assets/dcab7ac3-1ae4-462e-ad8a-057b32b1d776" />
  
#### ⚠️ Notes
- Pearson’s 𝑟 measures only linear correlation.
- It is sensitive to outliers.
- A high correlation does not imply causation.
- For non-linear relationships, consider alternatives (e.g., Spearman’s rank correlation).

---
## 🖼 View Graphs

<p align="left"><img width="712" height="631" alt="image" src="https://github.com/user-attachments/assets/ee8a1da7-1945-4833-9d25-36490f4e3614" />
 
  ### 📊 Table. R² Analysis for Each Condition in the Hole Chamber

| Graph | Condition             | Coating Thickness Std. Dev. R² | Average Pressure R² |
|-------|------------------------|-------------------------------|---------------------|
| (a)   | Non-baffle, 0.05 kPa   | 0.866                         | 0.920               |
| (b)   | Non-baffle, 0.15 kPa   | 0.997                         | 0.919               |
| (c)   | Baffle, 0.05 kPa       | 0.722                         | 0.922               |
| (d)   | Baffle, 0.15 kPa       | 0.808                         | 0.921               |

<p align="left"><img width="712" height="631" alt="image" src="https://github.com/user-attachments/assets/04fbf55f-8dd4-4214-aa26-53038d1c5541" />

  ### 📊 Table. R² Analysis for Each Condition in the Slit Chamber

| Graph | Condition             | Coating Thickness R² | Pressure Std. Dev. R² |
|-------|------------------------|-----------------------|------------------------|
| (a)   | Non-baffle, 0.05 kPa   | 0.5093                | 0.3391                 |
| (b)   | Non-baffle, 0.15 kPa   | 0.867                 | 0.341                  |
| (c)   | Baffle, 0.05 kPa       | 0.483                 | 0.9095                 |
| (d)   | Baffle, 0.15 kPa       | 0.5531                | 0.9405                 |
  
---
  
## ✅ Conclusion

In hole chambers, coating uniformity is strongly influenced by average pressure regardless of baffle use. In slit chambers, adding a baffle significantly enhances flow stability and coating quality, especially at low pressure. Pressure fluctuation consistently correlates with coating thickness variation. **Optimizing structure and pressure is essential for uniform film formation**.

---
