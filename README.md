# ⚽ FIFA World Cup Analysis | Correspondence Analysis (AFC)

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
|
├── report/
│ └── AFC_Project_Report.pdf
│
├── visuals/
│ ├── scree_plot.png
│ ├── le biplot de lignes et colonnes.png
│ ├── Afficher le graphique des points lignes colorés.png
│ └── tableau de contingence en diagramme a bulle.png
│
│
├── README.md
└── requirements.txt

```

---

## 📊 Visualizations

### 🔹 Scree Plot
![Scree Plot](visuals/scree_plot.png)

### 🔹 Biplot (Teams vs Results)
<img width="1069" height="628" alt="le biplot de lignes et colonnes" src="https://github.com/user-attachments/assets/ec33a1cf-80d3-4ba9-a26a-92793cb791d3" />


### 🔹 Row Points (Teams Distribution)
<img width="1373" height="654" alt="Afficher le graphique des points lignes colorés " src="https://github.com/user-attachments/assets/6783cce0-3f64-43db-bf93-231e2f51ea2d" />


### 🔹 Contingency Table Visualization
<img width="953" height="570" alt="tableau de contingence en diagramme a bulle" src="https://github.com/user-attachments/assets/5fdcef0c-530f-44d1-88d2-10112ee3ef3d" />


---

## 📈 Key Results
- First dimension explains **78.7% of variance**
- Second dimension explains **21.3%**
- Total variance explained = **100%**
- Strong statistical significance confirmed by **Chi-square test**

---

## 🧠 Key Insights
- Top-performing teams such as **Brazil, Germany, and France** are strongly associated with **winning outcomes**
- Some teams show a tendency toward **draw-heavy performance**
- Lower-performing teams are more associated with **losses**
- Correspondence Analysis clearly separates teams based on performance profiles

---

## 💡 Business Value
This analysis can be applied to:
- 📊 Sports analytics → Evaluate team performance trends
- ⚽ Coaching strategies → Understand strengths and weaknesses
- 📈 Data storytelling → Transform raw data into insights
- 🧠 Decision-making → Support performance-based evaluations

---

## ▶️ How to Run

Install dependencies:

```
pip install -r requirements.txt

```

Run notebook:

```
jupyter notebook notebooks/afc_analysis.ipynb

```
---

## 👩‍💻 Author
**Souad Zriouil**  
AI Engineer | Data Scientist | Machine Learning | NLP | LLM  

🔗 LinkedIn: https://www.linkedin.com/in/souad-zriouil-54b19b267/
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
