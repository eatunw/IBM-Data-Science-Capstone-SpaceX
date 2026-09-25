# IBM Data Science Capstone — SpaceX Falcon 9 Landing Prediction

## Project Overview
This capstone project predicts whether the SpaceX Falcon 9 first stage will land successfully, enabling cost estimation for rocket launches. The project follows the full data science pipeline: data collection, wrangling, EDA, interactive visualization, and machine learning classification.

## Repository Contents

### Notebooks
- `notebooks/jupyter-labs-spacex-data-collection-api.ipynb` — Data collection via SpaceX REST API
- `notebooks/jupyter-labs-webscraping.ipynb` — Web scraping Falcon 9 launch records from Wikipedia
- `notebooks/labs-jupyter-spacex-Data wrangling-v2.ipynb` — Data wrangling and label creation
- `notebooks/jupyter-labs-eda-sql-coursera_sqllite.ipynb` — EDA with SQL queries
- `notebooks/jupyter-labs-eda-dataviz-v2.ipynb` — EDA with visualization (matplotlib, seaborn)
- `notebooks/lab-jupyter-launch-site-location-v2.ipynb` — Interactive maps with Folium
- `notebooks/SpaceX-Machine-Learning-Prediction-Part-5-v1.ipynb` — ML classification models

### Dashboard
- `dashboard/spacex_dash_app.py` — Plotly Dash dashboard application
- `dashboard/spacex_launch_dash.csv` — Dataset used by the dashboard

### Presentation
- `presentation/Data Science Capstone Project Report.pdf` — Final presentation (PDF)

## Tools & Technologies
- **Languages:** Python, SQL
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, folium, plotly, dash, beautifulsoup4
- **Database:** SQLite
- **Platforms:** Jupyter Notebook, IBM Skills Network Lab

## Key Results
- **Best model:** Decision Tree Classifier
- **Test accuracy:** ~83.3%
- **Key predictors:** Orbit type, payload mass, booster version

## Author
[Atunde Emmanuel]
