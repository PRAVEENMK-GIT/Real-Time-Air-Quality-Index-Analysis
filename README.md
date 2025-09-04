# Real-Time Air Quality Index Analysis

This project analyzes real-time air quality data from Indian monitoring stations to identify pollution hotspots, compute AQI, and visualize trends. It uses Python data science libraries and includes a Jupyter notebook for reproducible analysis.

## Features
- Data cleaning and imputation for missing values
- Exploratory Data Analysis (EDA) with summary statistics and visualizations
- Feature engineering (AQI calculation, pollutant range, urban/rural classification)
- Clustering (KMeans) to identify pollution hotspots
- Regression modeling (RandomForest) to predict pollutant levels
- Evaluation metrics (Silhouette Score, RMSE, R²)
- Interactive geospatial mapping with Folium
- Export of key findings and results to CSV
- Versioned code and results

## Project Structure
- `air_quality_analysis.ipynb`: Main Jupyter notebook with all analysis steps
- `3b01bcb8-0b14-4abf-b6f2-c1bfd384ba69.csv`: Raw air quality dataset
- `cleaned_air_quality.pkl`: Cleaned dataset (pickle)
- `random_forest_model.pkl`: Trained regression model (pickle)
- `stations_map.html`: Interactive map of monitoring stations
- `top_polluted_cities.csv`: Top 10 polluted cities
- `air_quality_analysis_script.py`: Python script template for reproducibility

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/PRAVEENMK-GIT/Real-Time-Air-Quality-Index-Analysis.git
   cd Real-Time-Air-Quality-Index-Analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run `air_quality_analysis.ipynb` in Jupyter Notebook or VS Code.

## Requirements
- Python 3.8+
- pandas, numpy, matplotlib, seaborn, scikit-learn, folium

## Results
- Key findings and visualizations are available in the notebook and exported files.
- The project identifies pollution hotspots and predicts pollutant levels using machine learning.

## License
This project is licensed under the MIT License.

## Author
Praveen MK

---
Feel free to contribute or raise issues for improvements!
