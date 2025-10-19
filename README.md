<div align="left">

# 🎓 Graduate Admission Prediction using ANN

Predict graduate admission chances with deep learning! A complete workflow for data science beginners and advanced users.


</div>

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## Project Overview

This repository demonstrates how to use an Artificial Neural Network (ANN) to predict the probability of graduate admission based on academic and profile features. The project covers data loading, preprocessing, model building, training, evaluation, and prediction on new data.  
It is ideal for students, researchers, and anyone interested in machine learning for educational analytics.

---

## Features

- 📊 Loads and explores a real-world graduate admission dataset
- 🧹 Preprocesses data: feature selection, scaling, train-test split
- 🧠 Builds a sequential ANN using TensorFlow/Keras
- 🏋️‍♂️ Trains the model with validation and tracks performance
- 📈 Evaluates with R² score and visualizes training history
- 🔮 Predicts admission chances for new applicants

---

## Dataset

- **Source:** [Kaggle: Graduate Admission Dataset](https://www.kaggle.com/datasets/safaruzzamanshovo/graduate-admission-dataset)
- **Author:** Safaruzzaman Shovo
- **Features:**
  - GRE Score (out of 340)
  - TOEFL Score (out of 120)
  - University Rating (out of 5)
  - Statement of Purpose (SOP, out of 5)
  - Letter of Recommendation Strength (LOR, out of 5)
  - Undergraduate GPA (out of 4)
  - Research Experience (0 or 1)
  - Chance of Admit (0–1, target)

---

## Installation

1. **Clone the repository:**
              git clone https://github.com/SafaruzzamanShovo/Graduate-Admission-Prediction-using-ANN.git
2. **Install dependencies:**
             pip install pandas numpy scikit-learn tensorflow
3. **(Optional) Use Google Colab for easy Google Drive integration.**


---

## Usage

1. **Download the dataset** from Kaggle or Google Drive (see links above).
2. **Upload the dataset to your Google Drive** if using Colab.
3. **Open the notebook** (`Graduate_Admission_Prediction_using_ANN.ipynb`) in Colab or Jupyter.
4. **Run all cells** to train the ANN and evaluate its performance.
5. **Modify the 'new_data' cell** to predict admission chances for custom applicants.

---

## Model Architecture

- **Input:** 7 features (GRE Score, TOEFL Score, University Rating, SOP, LOR, GPA, Research)
- **Hidden layers:** 2 Dense layers (7 units each, ReLU activation)
- **Output:** 1 unit (Chance of Admit, linear activation)
- **Loss:** Mean Squared Error
- **Optimizer:** Adam
- **Epochs:** 150

---

## Results

- **R² Score:** ~0.88 (example from notebook)
- **Training/Validation Loss:** Visualized in notebook
- **Prediction Example:**

---

## Contributing

Contributions are welcome!  
Please fork the repository, create a pull request, or open an issue for suggestions and improvements.

---

## License

This project is for educational purposes.  
If you use the dataset or notebook, please cite Safaruzzaman Shovo as the dataset author.

---

## Acknowledgments

- Dataset by [Safaruzzaman Shovo](https://www.kaggle.com/safaruzzamanshovo)
- Inspired by open-source data science and machine learning communities

---

<div align="center">

Made with ❤️ for the data science community.

</div>


