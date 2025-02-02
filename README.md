# **Sports Prediction and Betting Model**

This repository trains and analyses a **random forest classifier** model for predicting the outcomes of competitive sports events. The project combines a systematic data-driven approach with a robust machine learning framework to provide probabilistic predictions for match outcomes. The model was applied to Major League Baseball (MLB) data and evaluated for both accuracy and profitability in a real-world betting context.

## **Repository Contents**

- **`Oddsportal scraper and data clean up.ipynb`**:  
  This notebook contains the code and workflow for scraping and preparing the required data from [oddsportal.com](https://www.oddsportal.com). It processes match statistics, odds, and other essential data for model training and evaluation.

- **`MLB.xlsx`**:  
  The dataset used for this project, containing match and odds statistics for the 2021–2024 MLB seasons. This includes team scores, match dates, and bookmaker odds for home and away wins.

- **`sports prediction and betting model.ipynb`**:  
  This notebook includes the implementation of the random forest classifier model. It evaluates the model's performance using the MLB dataset, calculates ROI, and provides insights into the profitability of the betting strategy.

- **`Sports_Prediction_Betting_Paper.pdf`**:  
  The accompanying paper details the theory, methodology, and analysis of the project. It provides a comprehensive explanation of the model's design, probability calibration, and performance metrics.

## **Key Features**
- Predicts match outcomes using a pairwise comparison approach based on a quantitative analysis of the relative performance of competing teams against shared opponents.
- Integrates the resulting features into a random forest classifier for probabilistic forecasting.
- Evaluates model performance against bookmaker accuracy and ROI on  a disciplined betting strategy.

## **Project Highlights**
- **Dataset**: Major League Baseball matches (2021–2024 seasons).
- **Return on Investment (ROI)**: Achieved a 1.95% ROI on 4431 matches using a disciplined betting strategy grounded in the Kelly criterion.
- **Performance Metrics**:
  - Brier Score (Model): 0.2452
  - Brier Score (Bookmaker): 0.2419

## **Dependencies & Libraries**
This project requires several Python libraries for **data collection, analysis, visualisation, and machine learning**:
- **Web Scraping**: `BeautifulSoup`, `selenium` – Used for extracting match data and odds from oddsportal.com.
- **Data Handling & Computation**: `pandas`, `numpy` – For managing and processing large datasets efficiently.
- **Machine Learning & Evaluation**: `scikit-learn` – Implements the **random forest classifier** and calculates performance metrics (Brier Score, accuracy, ROI).
- **Visualisation**: `matplotlib` – Generates charts and visual insights into betting performance and model calibration.


## **How to Use**
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/Sports_Prediction_and_Betting_Model.git
   cd Sports_Prediction_and_Betting_Model
2. Install the required Python libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib
3. Run the notebooks:
   - Start with `Oddsportal scraper and data clean up.ipynb` to generate or prepare data.
   - Use `sports prediction and betting model.ipynb` for model implementation and analysis.

4. Refer to `Sports_Prediction_Betting_Paper.pdf` for a detailed explanation of the project.

## **License**
This project is open-source under the [MIT License](LICENSE).

