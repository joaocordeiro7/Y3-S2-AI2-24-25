# Predicting Student Dropout and Academic Success

This project uses supervised machine learning models to predict student academic outcomes (Dropout, Enrolled, Graduate) based on historical data.

## Table of Contents
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Authors](#authors)

---

## Requirements

To run this project, ensure you have the following installed:
- Python 3.8 or higher
- Required Python libraries (see below)

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/proj2.git
   cd proj2
   ```

2. Install the requirede Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
   If ```requirements.txt``` is not available, install the libraries manually:
   ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
   ```
   
---

## Usage

1. Prepare the Dataset:

   Ensure the dataset file ```data.csv``` is in the root directory of the project.
Run the Program:

2. Execute the main script:
   ```bash
   python main.py
   ```
3. Output:

- The program will:
    - Load and preprocess the dataset.
    - Train and evaluate three machine learning models (Decision Tree, Random Forest, KNN).
    - Display the evaluation metrics for each model.

4. Jupyter Notebook:
or detailed analysis and visualization, open the ```SupervisedLearning.ipynb``` notebook:

   ```bash
    jupyter notebook SupervisedLearning.ipynb
    ```
---

## Project Structure

    proj2/
    ├── data.csv                     # Dataset file
    ├── main.py                      # Main script to run the program
    ├── README.md                    # Instructions and documentation
    ├── SupervisedLearning.ipynb     # Jupyter Notebook for detailed analysis
    ├── src/                         # Source code directory
    │   ├── data_loader.py           # Data loading module
    │   ├── preprocessing.py         # Data preprocessing module
    │   ├── model_selection.py       # Model training and evaluation module
    
---   

## Authors
This project was developed by Grupo A2_G101:

João Cordeiro (202205682)

Luciano Ferreira (202208158)

Tomás Telmo (202206091)
