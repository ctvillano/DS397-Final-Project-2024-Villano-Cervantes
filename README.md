# DS397-Final-Project-2024-Villano-Cervantes
DS 397 [TZQp] Advanced Mathematical Methods in Data Science
2nd Sem, A.Y. 2023-2024

## Binary Classification

### Loan Default Prediction: A Neural Network Approach

This project demonstrates how to build a basic neural network and apply it to a real-world dataset for predicting loan defaults.

### Data

We use a dataset from Lending Club, a peer-to-peer lending company. The dataset contains various features that describe the loans issued by the company.

### Neural Network Architecture

- **Input Layer**: 22 features
- **Hidden Layer**: 1 fully connected layer with (2/3) * input_features nodes
- **Output Layer**: 1 fully connected layer with 1 output node using the sigmoid activation function

### Optimizer

The optimizer used in this project is Mini Batch Stochastic Gradient Descent (SGD).

### Loss Function

For binary classification, we use **Binary Crossentropy** as the loss function.

<img src="https://latex.codecogs.com/svg.latex?\Large&space;L%20=%20-\left[y%20\ln(p)%20+%20(1-y)%20\ln(1-p)\right]" title="Binary Cross Entropy" />

where y is either 0 or 1, and p is the predicted probability.

---

### File Structure

- `loan_default_prediction.ipynb`: The main notebook containing the neural network implementation and analysis.
- `Data/Loan Prediction/`: The folder containing the dataset used for training and testing

---

### Contributors

- Celso Villano [ctvillano@up.edu.ph]
- Kristen Joyce Cervantes [krcervantes@up.edu.ph]


---
