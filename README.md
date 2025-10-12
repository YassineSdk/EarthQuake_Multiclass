---

# EarthQuake_Multiclass

Multiclass Classification of Earthquake Events in California and Los Angeles

## Overview

This project presents a comprehensive approach to the multiclass classification of earthquake events in California and Los Angeles. It utilizes data science and machine learning techniques to analyze seismic data, extract meaningful features, and build robust models for predicting earthquake types and characteristics.

The full project process, results, and insights are documented in the included [PDF report](./la-and-california-earthquake-classification.html.pdf).

## Project Objectives

- **Analyze earthquake datasets for California and Los Angeles**
- **Perform data preprocessing and feature engineering**
- **Apply and compare various classification algorithms**
- **Evaluate model performance and interpret results**
- **Provide actionable insights for seismic event classification**

## Data Description

The project uses publicly available earthquake datasets containing information such as:
- Event date and time
- Location (latitude, longitude, depth)
- Magnitude
- Event type (e.g., tectonic, explosion, quarry blast)

Data cleaning and preparation steps include handling missing values, encoding categorical variables, and normalizing numeric features.

## Methodology

1. **Exploratory Data Analysis (EDA)**
   - Visualization of geographical distribution, magnitude, and depth of events
   - Identification of main event types and their characteristics

2. **Feature Engineering**
   - Extraction of time-based, spatial, and event-type features
   - Transformation and encoding for machine learning readiness

3. **Model Selection**
   - Implementation of multiclass classifiers including:
     - Random Forest
     - Gradient Boosting
   - Hyperparameter tuning using grid search and cross-validation

4. **Model Evaluation**
   - Metrics: accuracy, precision, recall, F1-score, confusion matrix
   - Visualization of classification results and feature importances

5. **Result Interpretation**
   - Analysis of best-performing models
   - Insights into influential features


## Results

- The Random Forest and Gradient Boosting models showed the highest accuracy in multiclass classification.
- Feature importance analysis revealed that magnitude, depth, and location are critical for distinguishing event types.
- Geographical clustering of certain event types was observed, which can inform further geological studies.

## How to Use This Repository

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YassineSdk/EarthQuake_Multiclass.git
   ```

2. **Open the Jupyter Notebook:**
   - All code and stepwise analysis are provided in the notebook file.
   - You can run the notebook locally (with JupyterLab or VSCode) or on Google Colab.

3. **Read the PDF Report:**
   - For a complete walkthrough of the insights and findings, open [la-and-california-earthquake-classification.html.pdf](./la-and-california-earthquake-classification.html.pdf).

4. **Install the required packages:**
   - The notebook includes all necessary imports; ensure you have Python 3.8+ and standard ML/data libraries:
     ```
     pandas, numpy, scikit-learn, matplotlib, seaborn
     ```

## Repository Structure

- `la-and-california-earthquake-classification.html.pdf`: Main project report with detailed methodology and results
- `<notebook>.ipynb`: Source code for data analysis and modeling
- `data/`: (If included) Example datasets used for training and testing
- `README.md`: Project summary and instructions

## References & Credits

- USGS Earthquake Catalog
- Scikit-learn, Pandas, Matplotlib libraries

## License

This project is licensed under the MIT License.

---

**For more details, consult the PDF report and the Jupyter notebook in this repository.**

---

Would you like to add author information or further instructions for contributors? If so, please let me know and I’ll include them.
