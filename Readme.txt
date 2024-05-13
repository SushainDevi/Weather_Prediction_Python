
# Weather Data Analysis and Prediction

## Overview

This repository contains code for analyzing weather data and building a predictive model to forecast whether it will rain tomorrow in Sydney, Australia. The dataset used for analysis is provided in `Weather_Data.csv`.

## Key Features

- **Data Preprocessing**: The dataset undergoes preprocessing, including one-hot encoding of categorical variables (`RainToday`, `WindGustDir`, `WindDir9am`, `WindDir3pm`) and conversion of binary labels (`No`, `Yes`) to numerical values (`0`, `1`).

- **Model Building**: Logistic Regression is employed to build the predictive model. The dataset is split into training and testing sets using a 80-20 ratio.

- **Model Evaluation**: The trained model is evaluated using metrics such as accuracy, Jaccard score, F1 score, and log loss.

- **Visualization**: The distribution of the target variable (`RainTomorrow`) is visualized using a count plot. Additionally, correlation among features is displayed using a heatmap, and the confusion matrix for model performance evaluation is visualized.

## Usage

1. Clone the repository to your local machine.
2. Ensure Python and necessary libraries are installed (`pandas`, `scikit-learn`, `matplotlib`, `seaborn`).
3. Download the `Weather_Data.csv` file and place it in the root directory.
4. Run the provided script to analyze weather data and build the predictive model.
5. Follow the instructions in the script to interpret the results and visualize various aspects of the dataset and model performance.

## Acknowledgements

- The weather data used in this analysis is sourced from an open dataset.
- Special thanks to the contributors of `scikit-learn`, `matplotlib`, and `seaborn` libraries for providing useful tools for data analysis and visualization.

## License

This project is licensed under the [MIT License](LICENSE).

---
