# Fake-News-Classifier

This repository contains a Jupyter notebook (`fake_news.ipynb`) designed for the analysis and detection of fake news using machine learning and deep learning techniques. The notebook demonstrates the end-to-end process of data preprocessing, feature extraction, model building, and evaluation.

## Prerequisites

Ensure you have the following packages installed to run the notebook:
- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- TensorFlow: For building and training neural network models.
- Scikit-learn (sklearn): For data preprocessing, model evaluation, and machine learning utilities.
- Matplotlib: For generating visualizations. Note: Use `%matplotlib inline` in Jupyter notebooks to display plots inline.

## Dataset

The dataset used for this analysis is `WELFake_Dataset.csv`, available for download from [Kaggle](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification). It contains features and labels for news articles, classified as fake or real.

## Analysis Overview

The notebook includes the following key steps and methodologies:
1. **Data Preprocessing**: Initial data exploration and preprocessing to prepare the dataset for analysis.
2. **Feature Extraction**: Using `TfidfVectorizer` to convert text data into a matrix of TF-IDF features.
3. **Model Building**: Constructing a neural network model using TensorFlow's `Sequential` API with fully connected (`Dense`) layers.
4. **Model Training and Evaluation**: Splitting the data into training and testing sets, compiling the model, training it, and evaluating its performance using accuracy metrics.

## Getting Started

To run the notebook:
1. Clone this repository.
2. Ensure you have Jupyter Notebook installed and the above prerequisites are met.
3. Download the dataset from the provided Kaggle link and place it in the same directory as the notebook.
4. Open and run the `fake_news.ipynb` notebook.

## Contributing

Contributions to enhance the notebook are welcome. Feel free to fork the repository, make improvements, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
