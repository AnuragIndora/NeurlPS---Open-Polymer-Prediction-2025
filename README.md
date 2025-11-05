# 🧪 NeurIPS 2025: Open Polymer Prediction Challenge

**🥈 Silver Medal | Top 50 (Rank #50 / Score: 0.087)**  
**Competition:** [NeurIPS 2025 – Open Polymer Prediction](https://www.kaggle.com/competitions/neurips-2025-open-polymer-prediction)

---

## 🧬 Overview

This project was developed as part of the **NeurIPS 2025: Open Polymer Prediction** competition on Kaggle.  
The goal of the challenge was to **predict key polymer properties directly from their chemical structures**, enabling better design and discovery of novel materials.

---

## 🏆 Results

- 🥈 **Silver Medalist**
- 🌍 **Top 50 globally (Rank: 50)**
- 📈 **Final Score:** 0.087  

This was my **first Kaggle Silver Medal**, marking a milestone in my data science journey.

---

## ⚙️ Approach

### 🔹 Feature Engineering (RDKit)
Utilized the **RDKit** library to extract and compute molecular representations:
- **Physicochemical Descriptors** – e.g., molecular weight, LogP, TPSA  
- **Molecular Fingerprints** – *Morgan* (ECFP), *MACCS*, structural patterns  
- **Structural Features** – counts of atoms, bonds, functional groups  

### 🔹 Modeling
Explored and tuned multiple algorithms:
- **CatBoost**
- **LightGBM**
- **Random Forest**
- **Stacked Ensembles** (combining tree-based models for improved generalization)

### 🔹 Techniques
Key steps that improved performance:
- Data cleaning & preprocessing  
- Feature scaling & clipping  
- Cross-validation strategies  
- Model ensembling & weighted blending  

---

## 📊 Insights

Working on this problem deepened my understanding of:
- How **different molecular representations** affect predictive performance  
- The **trade-offs** between single-model simplicity and ensemble robustness  
- Practical aspects of **feature importance** and **model interpretability** in chemistry-related ML tasks  

---

## 🧠 Learnings & Reflections

This competition provided a hands-on opportunity to explore the intersection of **machine learning** and **computational chemistry**.  
It reinforced how thoughtful **feature engineering** and **ensemble modeling** can significantly boost results in structured scientific data problems.

I’m grateful to the **Kaggle community** and **NeurIPS organizers** for enabling such an inspiring and educational experience and I look forward to taking on more advanced challenges in the future.

---

## 📚 Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| **Languages** | Python |
| **Libraries** | RDKit, Pandas, NumPy, Scikit-learn, CatBoost, LightGBM |
| **Visualization** | Matplotlib, Seaborn |
| **Environment** | Kaggle Notebooks, JupyterLab |

---

## 🤝 Acknowledgements

A huge thanks to:
- **Kaggle community** for shared insights and discussions  
- **NeurIPS 2025 organizers** for curating an engaging, real-world problem  

---

**Author:** [AK](https://www.kaggle.com/evilak09)  
**Competition:** [NeurIPS 2025 – Open Polymer Prediction](https://www.kaggle.com/competitions/neurips-open-polymer-prediction-2025)
