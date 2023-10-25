# Heart Failure Prediction Using AI

![Heart Failure](https://img.shields.io/badge/Heart%20Failure-Prediction-blue)
![Python](https://img.shields.io/badge/Python-3.8%2B-green)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit%20Learn-orange)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-Plotly-blue)

This project is a data analysis and prediction tool for heart failure using AI. It utilizes various clinical parameters like ejection fraction, age, sex, diabetes, and more to predict the likelihood of heart failure in patients. The project's main goal is to demonstrate the potential of machine learning and data analysis in healthcare, specifically in predicting cardiovascular diseases.

## Dataset

The dataset used for this project is obtained from Kaggle, and it can be found [here](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data). It contains various features like age, anaemia, diabetes, ejection fraction, high blood pressure, and more, which are used for training the machine learning models.

## References

This project builds upon the work of various authors and leverages the following references:

- [Heart Failure Clinical Data](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data)
- [Heart Failure Prediction & Visualization](https://www.kaggle.com/sanchitakarmakar/heart-failure-prediction-visualization)
- [Data Visualization & Modeling (82% Accuracy, 75% F1 Score)](https://www.kaggle.com/isaienkov/data-visualization-modeling-82-acc-75-f1)
- [Heart Failure Analysis and Quick Prediction (96% Accuracy)](https://www.kaggle.com/nayansakhiya/heart-fail-analysis-and-quick-prediction-96-rate)
- [Plotly Hover Text and Formatting](https://plotly.com/python/hover-text-and-formatting/)
- [Creating and Updating Figures with Plotly](https://plotly.com/python/creating-and-updating-figures/)
- [Figure Labels in Plotly](https://plotly.com/python/figure-labels/)
- [Stack Overflow discussions](https://stackoverflow.com/questions/59993512/plotly-sunburst-typeerror-sunburst-got-an-unexpected-keyword-argument-path)
- [World Health Organization - Cardiovascular Diseases](https://www.who.int/health-topics/cardiovascular-diseases#tab=tab_1)

## Project Overview

The project involves the following steps:

1. Data Preprocessing: Data from the Kaggle dataset is cleaned, and any missing values are handled. Categorical features are encoded, and the data is split into training and testing sets.

2. Data Visualization: The project utilizes Plotly for data visualization. Various interactive plots and charts are generated to explore the data and understand the relationships between different features.

3. Machine Learning: Several machine learning algorithms are applied to predict heart failure. The models are trained on the dataset, and their performance is evaluated using metrics like accuracy, precision, recall, and F1 score.

4. Model Selection: The best-performing model is selected for heart failure prediction.

5. Deployment: The selected model is deployed and made available for use as a heart failure prediction tool.

## Installation

To run this project, you will need Python 3.8 or higher. You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone this repository to your local machine.

```bash
git clone https://github.com/yourusername/heart-failure-prediction.git
```

2. Navigate to the project directory.

```bash
cd heart-failure-prediction
```

3. Run the Jupyter Notebook or Python script to execute the analysis and prediction.

```bash
jupyter notebook Heart_Failure_Prediction.ipynb
```

or

```bash
python heart_failure_prediction.py
```

## Contributing

Contributions to this project are welcome! If you have suggestions, find issues, or want to add new features, please feel free to create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Thank you for using our Heart Failure Prediction project! If you have any questions or need assistance, feel free to reach out to us.

---
