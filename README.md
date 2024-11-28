<h1 align="center">
  <br>
  <a href="https://github.com/omerayvaz/ANN_Coursework/tree/main">
    <img src="https://github.com/omerayvaz/ANN_Coursework/blob/main/Media/img/KOUlogo.png" alt="Cardiovascular Disease Risk Prediction" width="200">
  </a>
  <br><br>
  Cardiovascular Disease Risk Prediction
  <br>
</h1>

*Developing a Neural Network from scratch to predict cardiovascular disease risk without relying on prebuilt Neural Network libraries.*

This project focuses on designing and implementing an Artificial Neural Network (ANN) model from scratch to accurately predict cardiovascular disease risk. For further details and to review the presentation in Turkish, click the link below:

[📂*View the Turkish Presentation...*](https://github.com/omerayvaz/ANN_Coursework/blob/main/CardiovascularDiseaseRiskPredictionUsingArtificialNeuralNetworks.pdf)


---

## 🛠️ Tools

The following tools and libraries were utilized in the development of this project:

- **Python:** General-purpose programming language.
- **Pandas:** For data reading, cleaning, processing, and analysis.
- **NumPy:** For mathematical computations and array manipulations.
- **Matplotlib & Seaborn:** For data visualization.
- **Scikit-learn:** For performance metrics and model evaluation.
- **Jupyter Notebook:** For prototyping and interactive development.


## 📂 3. Dataset

*📌 Dataset : [Cardiovascular Disease Dataset on Kaggle...](https://www.kaggle.com/datasets/akshatshaw7/cardiovascular-disease-dataset)*

### 🔍 3.1. Dataset Features

The dataset contains the following features related to cardiovascular diseases:

- **Age, Height, Weight, Gender:** Physical attributes.
- **Systolic and Diastolic Blood Pressure:** Blood pressure readings.
- **Cholesterol and Glucose Levels:** Blood test results.
- **Smoking, Alcohol Intake, Physical Activity:** Lifestyle indicators.
- **Target Variable (Cardio):** Presence or absence of the disease (0/1).

### ⚙️ 3.2. Data Preprocessing

<img src="https://github.com/omerayvaz/ANN_Coursework/blob/main/Media/Dataset.png" alt="Dataset Visualization" width="600">

- **Handling Missing Data:** Processing missing or outlier values.
- **Normalization:** Scaling features to a 0-1 range using *Min-Max normalization*.
- **Data Splitting:** Dividing the dataset into:
  - Training (70%)
  - Validation (15%)
  - Test (15%)
- **Correlation Matrix:** Selecting meaningful features for the model.

---

## 🤖 4. Model

A **dynamic structure** can be created, allowing flexibility in configuring the number of layers, neurons, and activation functions based on the task or dataset. This approach ensures adaptability for different use cases.  

#### **Example in Our Case:**

```python
# Define the neural network
nn = NeuralNetwork(input_size=9)

# Add hidden layers with ReLU activation
nn.add_hidden_layer('relu', 32)
nn.add_hidden_layer('relu', 128)
nn.add_hidden_layer('relu', 256)
nn.add_hidden_layer('relu', 64)

# Output layer with Sigmoid activation
nn.add_hidden_layer('sigmoid', 1)

# Train the model
costs = nn.train(X_train_transposed, y_train, X_val_transposed, y_val, epochs=300)
```


## **👥 Project Team**

📩📞 *For communication, feel free to reach out through the social media links provided on **our GitHub profiles.***

- **[Ömer Emircan Ayvaz](https://github.com/omerayvaz)**
- **[Muhammet Eren Gür](https://github.com/MuhammetErenGur)**
- **[Zeynep Aslı Erhan](https://github.com/zeynepaslierhan)**
- **[Eren Sezer](https://github.com/Erensz)**
- **[Eren Çalbay](https://github.com/erencalbay)**
- **[Fatih Özen](https://github.com/Fatihozn)**
- **[Mehmet Ali Akdoğan](https://github.com/Mali3215)**
- **[Ömer Faruk Ulusoy](https://github.com/omerulusoy41)**
