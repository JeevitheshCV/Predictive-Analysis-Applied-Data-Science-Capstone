
# Title: Predictive Analysis of SpaceX Falcon 9 Landings

# 🚀 IBM Applied Data Science Capstone – SpaceX Falcon 9 Landing Prediction

This repository contains the final project for IBM's Applied Data Science Capstone. The objective is to **predict whether the first stage of the SpaceX Falcon 9 rocket will land successfully**, which directly impacts launch cost efficiency.

## 📌 Objective

- Analyze historical launch data to identify features influencing landing outcomes.
- Create interactive visualizations and dashboards.
- Build and compare machine learning models for predictive analysis.

## 🧰 Tools & Technologies

- **Python**: Pandas, Numpy, Scikit-learn, Dash, BeautifulSoup
- **Visualization**: Matplotlib, Seaborn, Plotly, Folium
- **SQL**: SQLite for querying data
- **Jupyter Notebooks** for development

## 📂 Project Structure

- `/notebooks/`: All development notebooks
- `/data/`: Raw and processed datasets
- `/presentation/`: Final project presentation
- `requirements.txt`: Python dependencies

## 📊 Key Components

- **Data Collection**: SpaceX REST API & web scraping Wikipedia
- **Data Wrangling**: Feature engineering and cleaning
- **EDA**: Graphs, SQL queries, Folium maps
- **Dashboard**: Interactive Plotly Dash app to visualize payloads and outcomes
- **Modeling**: Logistic Regression, kNN, SVM, Decision Tree – Decision Tree chosen for its accuracy

## 📎 Notable Notebooks

- [Data Collection (API)](Notebooks/DataCollection_API.ipynb)
- [Web Scraping](Notebooks/DataCollection_Webscraping.ipynb)
- [EDA (Visual)](Notebooks/EDA_DataVisualization.ipynb)
- [EDA (SQL)](Notebooks/EDA_SQL.ipynb)
- [Dashboard](Notebooks/spacex_dash_app.py)
- [Machine Learning](Notebooks/Machine_Learning_Prediction.ipynb)


## 🎥 Presentation

📄 [Final Project Presentation (PDF)](Presentation/Final_Presentation.pdf)

## 💡 Key Insights

- Launch success is influenced by payload mass, orbit type, and launch site.
- Low-weight payloads tend to perform better.
- **KSC LC-39A** had the highest launch success rate.
- Decision Tree model selected due to superior training performance.

---

## 🔗 Project Links

- GitHub Repo: *https://github.com/JeevitheshCV/Predictive-Analysis-Applied-Data-Science-Capstone.git*




