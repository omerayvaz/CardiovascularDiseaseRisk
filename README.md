<h1 align="center">
  <br>
  <a href="https://github.com/omerayvaz/ANN_Coursework/tree/main">
    <img src="https://github.com/omerayvaz/ANN_Coursework/blob/main/Media/img/KOUlogo.png" alt="Cardiovascular Disease Risk Prediction" width="200">
  </a>
  <br><br>
  Cardiovascular Disease Risk Prediction
  <br>
</h1>

*Implementing a Neural Network from scratch for Cardiovascular Disease Risk Prediction without using Neural Network Libraries.*

---

## **Araçlar (Tools)**

The following tools and libraries were utilized in the development of this project:

- **Python:** General-purpose programming language.
- **Pandas:** For data reading, cleaning, processing, and analysis.
- **NumPy:** For mathematical computations and array manipulations.
- **Matplotlib & Seaborn:** For data visualization.
- **Scikit-learn:** For performance metrics and model evaluation.
- **Jupyter Notebook:** For prototyping and interactive development.


## **3. Dataset**

### **3.1. Dataset Features**

The dataset contains the following features related to cardiovascular diseases:

- **Age, Height, Weight, Gender:** Physical attributes.
- **Systolic and Diastolic Blood Pressure:** Blood pressure readings.
- **Cholesterol and Glucose Levels:** Blood test results.
- **Smoking, Alcohol Intake, Physical Activity:** Lifestyle indicators.
- **Target Variable (Cardio):** Presence or absence of the disease (0/1).

### **3.2. Data Preprocessing**

<img src="https://github.com/omerayvaz/ANN_Coursework/blob/main/Media/Dataset.png" alt="Dataset Visualization" width="600">

- **Handling Missing Data:** Processing missing or outlier values.
- **Normalization:** Scaling features to a 0-1 range using *Min-Max normalization*.
- **Data Splitting:** Dividing the dataset into:
  - Training (70%)
  - Validation (15%)
  - Test (15%)
- **Correlation Matrix:** Selecting meaningful features for the model.

---

## **4. Model**

### **4.1. Model Architecture**

- **Input Layer:** Number of neurons equal to the number of features in the dataset.
- **Hidden Layers:** Configurable number of layers using *ReLU activation function*.
- **Output Layer:** Binary classification using a *Sigmoid activation function*.

### **4.2. Optimization and Weight Initialization**

- **Optimization Algorithm:** *Adam optimizer* with:
  - β₁ = 0.9
  - β₂ = 0.999
  - ε = 1e-8
  - Learning Rate = 0.001
- **Weight Initialization:** Using *Xavier* and *He* methods to prevent gradient vanishing.

### **4.3. Training Process**

- **Loss Function:** *Binary Cross Entropy (BCE)*.
- **Forward and Backward Propagation:** Updating the model at each epoch during training.
- **Performance Monitoring:** Recording and visualizing training and validation losses.

---

## **5. Results**

### **5.1. Performance Metrics**

- **Accuracy:** *72.9%*
- **F1 Score:** *0.727*

<img src="https://github.com/omerayvaz/ANN_Coursework/blob/main/Media/ConfusionMatrix.png" alt="Confusion Matrix" width="600">

- **Confusion Matrix:** Displays the model's classification accuracy (*True Positives, True Negatives, False Positives, False Negatives*).

### **5.2. Visualizations**

<img src="https://github.com/omerayvaz/ANN_Coursework/blob/main/Media/CorrelationMatrix.png" alt="Correlation Matrix" width="600">

- **Training and Validation Losses:** Loss curves plotted across epochs.
- **Correlation Matrix:** Demonstrates the relationships between features used in the model.

### **5.3. Insights**

- The ANN model demonstrated reasonable accuracy in predicting cardiovascular disease.
- *Xavier and He weight initialization methods* effectively mitigated the gradient vanishing issue.
- Model performance can be further improved through careful hyperparameter tuning.

---

## **Proje Ekibi (Project Team)**

- **Ömer Emircan Ayvaz**
- **Muhammet Eren Gür**
- **Zeynep Aslı Erhan** *(zeynepaslierhan@gmail.com)*
- **Eren Sezer**
- **Ömer Faruk Ulusoy**
- **Eren Çalbay**
- **Fatih Özen**
- **Mehmet Ali Akdoğan**
