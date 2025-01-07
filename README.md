# job-change-prediction_dl_project
A deep machine learning project to predict the likelihood of students seeking job changes based on their demographics, education, experience, and training features. The project applies various regularization techniques to enhance model performance and reduce overfitting.

------------------

# Job Change Prediction  

## Overview  
This project leverages deep learning to predict whether an individual currently enrolled in a course at Zeta Analytics is likely to seek a job change. By analyzing demographic, educational, and professional data, the model assists the training institute in identifying and connecting potential job seekers with recruitment partners.  

---

## Features  
- **Data Preprocessing**:  
  - Handled missing values using median and mode imputation.  
  - Encoded categorical variables using One-Hot and Ordinal Encoding.  
  - Applied Min-Max Scaling to normalize numerical features for consistent gradient updates.  

- **Model Implementation**:  
  - Designed a binary classification model using PyTorch.  
  - Integrated multiple fully connected layers with ReLU activation.  
  - Utilized Sigmoid activation in the output layer for probability prediction.  

- **Regularization Techniques**:  
  - Implemented Dropout Layers, Batch Normalization, and L2 Regularization to reduce overfitting.  
  - Used Early Stopping to halt training when validation performance plateaued.  

- **Hyperparameter Optimization**:  
  - Leveraged **Optuna** to fine-tune hyperparameters such as learning rate, dropout rates, and the number of hidden layers.  

- **Evaluation Metrics**:  
  - Evaluated the model using AUC, Accuracy, Log Loss, and Confusion Matrix.  

---

## Skills and Technologies Used  
- **Python**  
- **PyTorch**  
- **NumPy**, **Pandas**  
- **Matplotlib**, **Seaborn**  
- **Optuna**  

---

## How to Use  

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/GovindaTak/job-change-prediction_dl_project.git
   ```  

2. **Navigate to the Project Directory**:  
   ```bash
   cd job-change-prediction  
   ```  

3. **Install Dependencies**:  
   ```bash
   pip install -r requirements.txt  
   ```  

4. **Run the Jupyter Notebook**:  
   ```bash
   jupyter notebook Job_Change_Prediction.ipynb  
   ```  

---

## Results and Insights  
- **Regularization Impact**: Techniques like Dropout and L2 Regularization enhanced the model's ability to generalize, reducing overfitting.  
- **Optimizer Performance**: Adam optimizer outperformed others with faster convergence and higher AUC scores.  
- **Hyperparameter Tuning**: Optuna provided optimal configurations, leading to better validation performance.  
- **Visualization**: Training and test loss curves demonstrated smooth convergence with minimized variance.  

---

## Project Structure  
- **Dataset**: Contains processed training and testing data.  
- **Notebook**: Includes steps for data preprocessing, model building, training, and evaluation.  
- **Results**: Features visualizations and detailed metrics to assess model performance.  

---

## License  
This project is licensed under the MIT License. See the LICENSE file for details.  

---
## Contact  
For questions or feedback, feel free to reach out at **govindatak19@gmail.com**.  
```
