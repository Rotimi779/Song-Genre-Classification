# Song-Genre-Classification

## Introduction
This project involves classifying music tracks into genres using machine learning techniques. The dataset includes various features extracted from music tracks, such as acousticness, danceability, energy, and more. The primary goal is to apply different classification models to predict the genre of a track, focusing on comparing the performance of a Decision Tree Classifier and a Logistic Regression model. The project also addresses class imbalance by balancing the dataset and evaluates the models using cross-validation.

## Objectives
The primary objectives of this project are:
   - Data preparation: Preprocess the data by scaling features and applying Principal Component Analysis (PCA).
   - Model Training and Evaluation:Train and evaluate a Decision Tree Classifier and a Logistic Regression model on the dataset, while also assessing model performance using classification reports and confusion matrices.
   - Cross Validation: Use K-Fold cross-validation to ensure that the models generalize well to unseen data.
 
## Requirements
Ensure  you have the following dependencies installed:
   - Python 3.x
   - pandas
   - numpy
   - scikit-learn
   - matplotlib


## Installation
To run this project, you need to install the following Python libraries:

```bash
git clone https://github.com/Rotimi779/Song-Genre-Classification.git
cd Song-Genre-Classification
pip install -r requirements.txt
```

## Usage
To use this repository, follow the following steps:
1. Clone the repository:
```bash
git clone https://github.com/Rotimi779/Song-Genre-Classification.git
```
2. Navigate to the project directory:
```bash
cd Song-Genre-Classification
```
3.Start Jupyter Notebook
```bash
jupyter notebook
```

## Evaluation
The models were evaluated based on their performance in predicting music genres, with a focus on precision, recall, and F1-score. Key findings include:

- Decision Tree Classifier:
     - Initial performance showed a bias towards the Rock genre.
     - After balancing the dataset, the model achieved better balance but still showed room for improvement.

- Logistic Regression:
     - The initial model demonstrated better performance for the Hip-Hop genre compared to the Decision Tree.
     - Post-balancing, the Logistic Regression model provided more balanced results across both genres.

- Cross-Validation Results:
     - Decision Tree: The model achieved a mean cross-validation score of approximately 0.735.
     - Logistic Regression: The model achieved a mean cross-validation score of approximately 0.781, indicating slightly better performance compared to the Decision Tree.

![Screenshot 2024-08-24 021256](https://github.com/user-attachments/assets/81c7bda5-ebeb-44dd-bc7b-48c309b82700)


Overall, balancing the dataset improved model performance, particularly for genres with fewer samples. The Logistic Regression model performed slightly better than the Decision Tree Classifier in the cross-validation tests.

## Contributions
Contributions for this project are welcome in order to improve it. To contribute, follow these steps:
1. Fork the repository: Click the "Fork" button at the top right of the repository page to create a copy of this repository on your GitHub account.
2. Clone the Repository: Clone your forked repository to your local machine.
```bash
git clone https://github.com/Rotimi779/Stock-Market-Analysis-Tool.git
```
3. Create a New Branch: Create a new branch for your feature or bug fix.
```bash
git checkout -b feature-name
```
4. Make Changes: Make your changes to the codebase.
5. Commit Your Changes: Commit your changes with a clear and descriptive commit message.
```bash
git commit -m "Description of your changes"
```
6. Push to Your Branch: Push your changes to your forked repository.
```bash
git push origin feature-name
```
7. Open a Pull Request: Open a pull request to merge your changes into the main repository. Provide a detailed description of your changes in the pull request.

Your contributions for this project are highly valued and will be reviewed as soon as possible. Thank you for your improvements to this project.
