**Predicting University Student Enrollment in Algeria: A Data-Driven Approach**  

---

### **Introduction**  
Predicting university enrollment is critical for educational planning, resource allocation, and policy development. Using Algeria’s historical tertiary education enrollment data (1971–2018), this analysis employs linear regression to forecast future student numbers, offering insights into potential trends and challenges.  

---

### **Methodology**  

#### **1. Data Preparation**  
The dataset was filtered to extract tertiary enrollment figures under the indicator *“Enrolment in tertiary education, all programmes, both sexes (number).”* Missing values were removed, and years were sorted chronologically to ensure accuracy.  

#### **2. Trend Analysis**  
Historical data revealed a **steady upward trend** (Fig. 1):  
- **1971–2000**: Slow growth, peaking at ~549,000 students.  
- **2001–2018**: Rapid expansion, reaching 1.6 million students by 2018.  

This growth aligns with Algeria’s investments in higher education infrastructure and rising literacy rates.  

---

### **Model Development**  
A **linear regression model** was trained on 80% of the data (1971–2010), with the remaining 20% (2011–2018) used for validation.  
![image](https://github.com/user-attachments/assets/aded7661-8e20-49ac-8ac2-d326db4b36e1)

#### **Key Metrics**  
- **Mean Absolute Error (MAE)**: 52379.74 students  
- **R-squared**: 0.9703 (indicating a strong fit to historical trends).  

---

### **Predictions for 2024**  
Using the trained model, university enrollment in Algeria is projected to reach **1.86 million students by 2024** 
⑴<img width="675" alt="Capture d'écran 2025-02-13 2231125" src="https://github.com/user-attachments/assets/620f8d06-e513-4a68-a71d-7b028c487b73" />


---

### **Key Insights**  
1. **Growth Drivers**:  
   - Demographic shifts (youth population growth).  
   - Government policies promoting higher education access.  

2. **Limitations**:  
   - Assumes linear trends; external factors (economic downturns, policy changes) may alter trajectories.  
   - Limited data on variables like funding or employment rates.  

---

### **Recommendations**  
1. **Infrastructure Expansion**: Address overcrowding in universities.  
2. **Policy Flexibility**: Prepare for demographic changes.  
3. **Enhanced Data Collection**: Incorporate socioeconomic variables for robust predictions.  

---

### **Conclusion**  
This analysis highlights Algeria’s growing demand for tertiary education. While the model provides a baseline, integrating broader datasets will refine accuracy and support sustainable educational planning.  

---
**Note on Dataset Indicators**  

This dataset contains a large number of education-related indicators from the **World Bank Education Statistics Database**. Each indicator represents a specific aspect of education, such as enrollment, completion rates, literacy, and expenditure.  

To explore other indicators, you can simply **change the indicator code** while keeping the structure of the dataset. 
<img width="502" alt="image" src="https://github.com/user-attachments/assets/225a0100-4e9b-4856-b136-dd813c37575d" />
 

For example:  
- **SE.PRM.ENR** → Primary school enrollment  
- **SE.SEC.ENR** → Secondary school enrollment  
- **SE.TER.ENR** → Tertiary (higher) education enrollment  

Similarly, you can find indicators related to **teachers, expenditure, literacy rates, and more** by modifying the code. Visit the **World Bank Open Data Portal** ([[https://data.humdata.org/dataset/world-bank-education-indicators-for-algeria])) to check the full list of available indicators.

⑴https://www.aps.dz/ar/sante-science-technologie/168710-2025-2024-800#:~:text=%D8%A7%D9%84%D8%AF%D8%AE%D9%88%D9%84%20%D8%A7%D9%84%D8%AC%D8%A7%D9%85%D8%B9%D9%8A%202025%2F2024%20%3A%20%D8%A3%D8%B2%D9%8A%D8%AF,%D8%A8%D8%A7%D9%84%D8%AC%D8%A7%D9%85%D8%B9%D8%A7%D8%AA%20%D8%B9%D8%A8%D8%B1%20%D9%85%D8%AE%D8%AA%D9%84%D9%81%20%D9%88%D9%84%D8%A7%D9%8A%D8%A7%D8%AA%20%D8%A7%D9%84%D9%88%D8%B7%D9%86


🔗 [LinkedIn Profile](https://www.linkedin.com/in/abdessamed-ouahabi)

