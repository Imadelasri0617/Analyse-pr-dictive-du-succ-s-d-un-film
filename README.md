# Analyse prédictive du succes d'un film
<<<<<<< HEAD
Un tableau de bord interactif Streamlit qui analyse et prédit le succès des films à l'aide d'indicateurs clés de performance tels que le budget, les recettes, la popularité, la durée et le nombre moyen de votes. Développé en Python, ce projet exploite la visualisation des données, les tests statistiques et Machine Learning
=======

Un tableau de bord interactif Streamlit qui analyse et prédit le succès des films à l'aide d'indicateurs clés de performance tels que le budget, les recettes, la popularité, la durée et le nombre moyen de votes. Développé en Python, ce projet exploite la visualisation des données, les tests statistiques et Machine Learning.

---



---

## 📊 Key Features

- 🎯 Permet de prédire si un film a des chances de succès (Recettes > Budget)
- 📈 Visualisation des données à l'aide de Seaborn et Matplotlib (Budget vs Revenus, Tendances par genre)
- 📊 Tests statistiques :T-Test and Chi-Square  
- 🤖 Random Forest Classifier pour la prédiction du succès
- 🧠 Filtrage interactif par genre et moyenne des votes via la barre latérale
- 🧼 Tableau de bord épuré et modulaire, prêt à être déployé

---

## 🧰 Tech Stack

- **Python** 🐍
- **Pandas**, **NumPy**
- **Seaborn**, **Matplotlib**
- **Scikit-learn**
- **Streamlit**
- **SciPy**

---

## 📷 Screenshots

| Dashboard Overview | Statistical Tests |
|--------------------|-------------------|
| ![Dashboard](assets/dashboard.png) | ![Tests](assets/stats_tests.png) |

> Add more screenshots to the `assets/` folder and reference them similarly.

---

## 🚀 Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/nv2105/MovieIQ-Predictive-Analytics-on-Film-Success.git
cd MovieIQ-Predictive-Analytics-on-Film-Success
 
```
### 2. Install dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the app
```bash
streamlit run MovieIQ.py
```
## 📁 Dataset
Make sure the project includes a `movies.csv` file with the following columns:<br>
` budget, revenue, popularity, runtime, vote_average, title, genres`
<br>
## 👨‍💻 Author<br>
### Naman Vora<br>
#### Final Year CSE Student | Aspiring Data Analyst<br>
📫 [LinkedIn](www.linkedin.com/in/namanvora21) • [GitHub](https://github.com/nv2105)

## 📄 License
This project is open source and available under the [MIT License.](https://mit-license.org/) 
>>>>>>> e9a056c (first commit)
