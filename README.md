# ⚽ FIFA World Cup Teams Performance Analysis (AFC)

## 📌 Overview
This project analyzes the **performance of national football teams** in the FIFA World Cup (up to 2022) using **Correspondence Analysis (AFC)**.

The objective is to explore **relationships between teams and match outcomes** (wins, draws, losses) and uncover hidden performance patterns.

---

## 🎯 Objectives
- Perform Exploratory Data Analysis (EDA)
- Analyze relationships between teams and results
- Apply Chi-square test
- Perform Correspondence Analysis (AFC)
- Visualize results using different plots
- Extract meaningful insights

---

## 📂 Dataset
The dataset contains historical performance of national teams in FIFA World Cup.

### Variables:
- **Team** → National team  
- **W** → Wins  
- **D** → Draws  
- **L** → Losses  

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- R (FactoMineR, factoextra)
- Excel (XLSTAT)
- Statistics (Chi-square, AFC)

---

## ⚙️ Project Structure

```

fifa-world-cup-afc-analysis/
│
├── data/
│ └── donnees_nettoyees_Coupe_du_monde.xlsx
│
├── notebooks/
│ └── afc_analysis.ipynb
│
├── visuals/
│ ├── scree_plot.png
│ ├── le biplot de lignes et colonnes.png
│ ├── Afficher le graphique des points lignes colorés.png
│ └── tableau de contingence en diagramme a bulle.png
│
├── report/
│ └── AFC_Project_Report.pdf
│
├── requirements.txt
└── README.md

```

---

## 📊 Visualizations

### 🔹 Scree Plot
![Scree Plot](visuals/scree_plot.png)

### 🔹 Biplot (Teams vs Results)
![Biplot](visuals/biplot.png)

### 🔹 Row Points (Teams Distribution)
![Row Points](visuals/row_points.png)

### 🔹 Contingency Table Visualization
![Contingency](visuals/contingency_bubble.png)

---

## 📈 Key Results
- First dimension explains **78.7% of variance**
- Second dimension explains **21.3%**
- Total variance explained = **100%**

---

## 🧠 Insights
- Strong teams (Brazil, Germany, France) are associated with **wins**
- Some teams are more associated with **draws**
- Others are linked to **losses**
- AFC clearly separates teams based on performance

---

## ▶️ How to Run

Install dependencies:

pip install -r requirements.txt

Run notebook:

jupyter notebook notebooks/afc_analysis.ipynb

---

## 👩‍💻 Author
**Souad Zriouil**  
AI Engineer | Data Scientist | Machine Learning | NLP | LLM  

🔗 LinkedIn: https://www.linkedin.com/

---

## ⭐ Project Value
This project demonstrates:
- Advanced statistical analysis (AFC)
- Data cleaning and preprocessing
- Data visualization and interpretation
- Real-world data analysis skills

---

## 🚀 Conclusion
This project highlights how Correspondence Analysis can be used to understand relationships between teams and performance, providing valuable insights into World Cup history.
