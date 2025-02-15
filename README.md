# Weather Prediction with PyTorch 🌦️🤖

This project demonstrates **binary classification** using **PyTorch** to predict whether it will rain tomorrow based on weather data. The goal is to classify whether it will rain ("Yes" or "No") using features such as temperature, humidity, and wind speed. 🎯📊

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **PyTorch** to build and train a neural network for binary classification. 🤖📈
- Leverages weather data from the **Australian Weather Dataset**. 🧠🔍
- Implements data preprocessing, model training, and evaluation. 📊📉

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install torch pandas numpy matplotlib seaborn scikit-learn tqdm
```

---

## Usage 🖥️

1. **Load Dataset**: The script downloads and loads the Australian Weather Dataset.
2. **Preprocess Data**: Handles missing values, encodes categorical variables, and splits the data into training and test sets.
3. **Build Model**: Defines and trains a neural network for binary classification.
4. **Evaluate Model**: Evaluates the model's performance using accuracy, classification reports, and confusion matrices.

---

## Code Structure 🗂️

- **Data Preparation**:
  - Downloads and preprocesses the weather dataset.
  - Splits the data into training and test sets.

- **Model Definition**:
  - Defines a neural network with multiple hidden layers and batch normalization.
  - Uses binary cross-entropy loss for training.

- **Training**:
  - Trains the model using the training set.
  - Tracks training and test accuracy and loss.

- **Evaluation**:
  - Evaluates the model's performance on the test set.
  - Visualizes results using classification reports and confusion matrices.

---

## Results 📊

- **Training/Test Accuracy**: The model achieves high accuracy on the training and test sets.
- **Classification Report**: Provides precision, recall, and F1-score for each class.
- **Confusion Matrix**: Visualizes the model's predictions against actual labels.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model's training progress:

```plaintext
Epoch 0: Train set - loss: 0.364, accuracy: 0.851
Epoch 100: Train set - loss: 0.123, accuracy: 0.987
```

---

## Dependencies 📦

- `torch`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `tqdm`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝
