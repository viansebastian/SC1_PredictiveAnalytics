# Study Case 1: Predictive Analytics in Diamonds Market

### Business Understanding

**Company Goals:**

Menerapkan automasi pada sistem dalam memprediksi harga diamonds dengan teknik predictive modelling.

Harga berlian dipengaruhi:
- karat
- bentuk potongan
- warna
- tingkat kejernihan


**Problem statement**

- Dari serangkaian fitur-fitur, apa yang paling berpengaruh terhadap harga diamonds?
- Berapa harga pasar diamnonds dengan karakteristik/fitur tertentu?

**Predictive Modelling Goals:**

- Mengetahui fitur yang paling berkorelasi dengan harga diamonds
- Membuat model ML yang dapat memprediksi harga diamonds seakurat mungkin

*Metodologi*:

Harga --> Variabel Kontinu = Kasus Regresi


*Metrik*:

Metrik umum dalam kasus Regresi
- Mean Squared Error (MSE)
- Root Mean Square Error (RMSE)


*Models*:
- K-Nearest Neighbor
- Random Forest
- Boosting Algorithm

---
Some data analysis methods covered in this notebook, as seen from the visualizations are: 

1. **Outliers Detection and their handling using IQR method**
---

![Cute Cat](box.png?raw=true "Outliers Detection")

2. **Data distribution understanding**
---

![Cute Cat](dist.png?raw=true "Data Dist")

3. **Correlation matrix**

--- 

![Cute Cat](corr.png?raw=true "correlation matrix")

4. **Pair plots**
--- 

![Cute Cat](numv.png?raw=true "numerical features")

Models used in this notebook, to predict and solve this regression problem, are KNN, Random Forest, 
and the AdaBoost Boosting Algorithm. 

**The results of them can be seen as follows.**

--- 

![Cute Cat](results.png?raw=true "results")
