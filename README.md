### Simple Feedback Learning
Simple Feedback Learning for emotion classification (dataset from: https://www.kaggle.com/praveengovi/emotions-dataset-for-nlp)

Uses correct/incorrect feedback and info about (y>d) or (y<d) to change weights.  
- 1. Implements forward and calculate the output 
- 2. Updates the weights and bias
- 3. Predicts function 
- 4. Uses activation function

### Evaluator Function
Implements an evaluator function with Pytorch or Numpy only. Evaluation metrics includes confusion matrix, accuracy, recall score, precision and F1 score.

### Train and Evaluate the Model
Trains the model with customized learning rate and number of iterations. Uses the predict function to predict the labels with the test dataset. Evaluates the prediction results.
