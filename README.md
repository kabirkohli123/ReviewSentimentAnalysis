# ReviewSentimentAnalysis


This repository contains a project focused on sentiment analysis of restaurant reviews. The goal is to predict whether a review is positive (liked) or negative (not liked) using various machine learning models.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models Used](#models-used)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

The project aims to analyze the sentiment of restaurant reviews using machine learning algorithms. By training models on a labeled dataset of reviews, the project predicts if a review is positive or negative. This analysis can help businesses understand customer satisfaction and improve their services.

## Dataset

The dataset used for this project is a collection of restaurant reviews labeled with sentiment (positive or negative). 

- **File:** `a1_RestaurantReviews_HistoricDump.tsv`
- **Format:** Tab-separated values (TSV) with two columns: 
  - `Review` - The text of the review.
  - `Liked` - A binary label indicating whether the review is positive (1) or negative (0).

## Installation

To run this project locally, you'll need Python 3 and several Python libraries. Follow these steps to set up the environment:

1. Clone the repository:
    ```bash
    git clone https://github.com/kabirkohli123/Restaurant-Sentiment-Analysis.git
    cd Restaurant-Sentiment-Analysis
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

## Usage

1. Open the Jupyter Notebook `ResturantSentimentAnalysis.ipynb`.
2. Follow the steps in the notebook to load the dataset, preprocess the data, train the models, and evaluate their performance.
3. To make predictions on new data, run the provided input section code in the notebook.

## Models Used

The following machine learning models are used in this project:

- **Support Vector Machine (SVM)**
- **Random Forest Classifier**
- **XGBoost Classifier**

Each model is trained on the TF-IDF features extracted from the text reviews to predict the sentiment.

## Results

After training and evaluating the models, the XGBoost classifier provided the highest accuracy in predicting the sentiment of restaurant reviews. Here are the key performance metrics:

- **Accuracy:** [81.5%]

For detailed performance metrics, refer to the `ResturantSentimentAnalysis.ipynb` notebook.

## Contributing

Contributions are welcome! If you want to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.
