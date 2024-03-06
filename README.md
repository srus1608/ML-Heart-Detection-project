### Heart Disease Detection

### Overview
This project aims to develop a machine learning model for predicting the likelihood of heart disease in patients based on various medical factors. 
The model is trained on a dataset containing information such as age, sex, chest pain type, resting blood pressure, cholesterol level, and other relevant features.

### Table of Contents
1. Installation
2. Usage
3. Dataset
4. Model Development
5. GUI Implementation
6. Contributing
### Installation
To run the project locally, follow these steps:

### 1. Clone the repository:
git clone https://github.com/srus1608/ML-Heart-Detection-Project.git

### 2. Navigate to the project directory:
cd ML-Heart-Detection-Project

### 3. Install the required dependencies:
pip install -r requirements.txt

### Usage
Once the project is set up, you can use the graphical user interface (GUI) to predict the likelihood of heart disease. Run the following command to launch the GUI:

python gui.py

Enter the required medical data into the input fields and click the "Submit" button to view the prediction result.

### Dataset
The dataset used for training the machine learning model is available in the heart.csv file. 
It contains avarious  samples and  features, including age, sex, chest pain type, and other medical attributes.
### Link od Dataset

Can download from here : https://www.kaggle.com/datasets/johnsmith88/heart-disease-datas

### Model Development
The machine learning model is developed using the RandomForestClassifier from the scikit-learn library. Various preprocessing techniques such as handling missing values and feature 
scaling are applied to the dataset before training the model.

### GUI Implementation
The graphical user interface (GUI) is created using the Tkinter library in Python. It provides an intuitive interface for users to input their medical data and view the prediction result.

### Contributing
Contributions to the project are welcome! If you'd like to contribute, please fork the repository, make your changes, and submit a pull request. 
For major changes, please open an issue first to discuss the proposed changes.



