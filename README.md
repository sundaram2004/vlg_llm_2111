LLM - Detect AI Generated Text
This repository contains code for detecting AI-generated essays using machine learning techniques. The model is trained on a dataset of essays labeled as either human-written or AI-generated.

Introduction
AI-generated content poses a challenge in various applications, including essays. This project aims to detect AI-generated essays using a Support Vector Machine (SVM) model trained on a dataset of labeled essays.
Dataset
The dataset used for training and evaluation is available in the data directory. It includes essays labeled as either human-written (class 0) or AI-generated (class 1). The dataset is divided into training and testing sets.


Prerequisites
•	Python 3
•	Jupyter Notebook (for running the code interactively)


Installation
1.	Clone the repository:
bashCopy code
git clone https://github.com/yourusername/essay-generator-detection.git cd essay-generator-detection 
2.	Install the required dependencies:
bashCopy code
pip install -r requirements.txt 


Usage
1.	Run the Jupyter Notebook Essay_Generator_Detection.ipynb for training and evaluating the model.
2.	The trained model will be saved, and you can use it to predict whether a given essay is AI-generated.


Results
•	The model achieves high accuracy in detecting AI-generated essays. Check the ROC curve in the notebook for more details.
•	The submission file (submission.csv) contains the predicted probabilities for AI-generated essays on the test set.


