Project: CNN and Hybrid Classifiers for Weed–Crop Seedling Classification
Author

Student: LP Mbiza (19064722)

Course: COS 801 – Introduction to Deep Learning

Assignment: Homework 1

1. Project Description

This project implements and evaluates convolutional neural network (CNN)-based approaches for classifying weed vs. crop seedlings using an agricultural dataset of 12 plant species.

Three models are compared:

Baseline CNN – Standard CNN with softmax classifier.

CNN + SVM – CNN feature extraction with Support Vector Machine classifier.

CNN + XGBoost – CNN feature extraction with XGBoost classifier.

The objective is to investigate which approach yields the best classification performance using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

This aligns with UN SDG Goal 2: Zero Hunger, supporting sustainable agriculture by automating weed detection
.

2. Folder Structure
├── MIT801 HW1 LP MBIZA (19064722).ipynb   # Jupyter Notebook with full implementation
├── data/                                
│   ├── train.
│   ├── test.
│   
│   
├── Requirements.txt                        
└── README.txt                            

3. Requirements

Run the project using Anaconda (Python 3.9+). Install dependencies with:

pip install -r requirements.txt

Main Libraries:

numpy

pandas

matplotlib

seaborn

scikit-learn

tensorflow / keras

xgboost

4. Dataset

The dataset contains 12 classes of seedlings (e.g., chickweed, black grass, fat hen, maize, sugar beet).

Training data: train/ images

Testing data: test/ images

Dataset link (provided in assignment):
Google Drive – Plant Seedlings Dataset

Place the dataset inside the data/ folder before running the notebook.

5. Running the Notebook

Launch Jupyter Notebook inside Anaconda Navigator:

jupyter notebook


Open MIT801 HW1 LP MBIZA (19064722).ipynb.

Run all cells sequentially.

Results (classification reports, ROC curves, and comparison plots) will be generated and displayed inline.

6. Outputs

The notebook produces:

Training/validation accuracy & loss plots

ROC curve plots

Precision, Recall, F1-score tables

Performance comparison between CNN, CNN+SVM, and CNN+XGBoost

7. Notes

Ensure the dataset is properly extracted inside the data/ folder.

Running CNN models may require GPU acceleration for efficiency.

Hyperparameters (filters, kernel sizes, activation functions) can be adjusted in the notebook.