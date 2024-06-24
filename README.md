## Predicting Airport Centrality with MLP using Passenger Data (On going)

This project demonstrates the application of a Multilayer Perceptron (MLP) to predict various centrality measures of airports using passenger data. The aim is to understand how passenger traffic influences an airport's role in the aviation network.

### Data Preparation

- **Features and Targets**: The passenger data (e.g., total passengers, domestic, international) serve as input features, while centrality indices (e.g., degree, closeness, betweenness) are the targets.
- **Training and Test Split**: Data is split into 80% for training and 20% for testing.
- **Normalization**: Input data is standardized to have zero mean and unit variance to ensure efficient training.

### MLP Model Definition

- **Framework**: Implemented using Keras.
- **Architecture**:
  - **Input Layer**: Size corresponds to the number of passenger data features.
  - **Hidden Layers**: Two hidden layers, each with 64 neurons and ReLU activation.
  - **Output Layer**: Consists of 7 neurons, each representing a centrality measure.
- **Compilation**: The model uses the Adam optimizer and mean squared error (MSE) for loss calculation.

### Training the Model

- The model is trained with passenger data as inputs and centrality indices as outputs.
- Training involves monitoring loss on both training and validation datasets to ensure convergence and generalization.

### Model Evaluation

- **Performance**: The trained MLP is evaluated using the test dataset with metrics such as MSE, mean absolute error (MAE), and R-squared.

### Model Tuning

- Adjustments can be made to the MLP’s architecture, optimizer settings, and regularization techniques to optimize performance.

### Prediction

- The trained model can predict the centrality of airports based on new passenger data, helping to gauge their network significance.

### Conclusion

Using MLP to model the relationship between passenger data and airport centrality provides valuable insights into how traffic influences an airport’s network position. This approach highlights the potential of machine learning in transportation and network analysis.
