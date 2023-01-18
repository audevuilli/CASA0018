## CASA0018 Week 2

An overview of models' architecture. 

Question 1 - Why adding  dense layers to a model? 
- (+) Learn more complex representations of the input data. First layer extracts low-level features, subsequent layers can extract higher-level features. Improve performance of the model, as more abstract concepts can be learn. 
- (-) Overfitting or too large and heavy model for the task to solve. 

Question 2 - How many neurons should there be in each layer of a model?
- No one-size-fits-all answer to how many neurons to use. 
- Number of neurons depend on the complexity of the input data and the task to solve.
- Experiment with different values of neurons. Many neurons allow the model to learn complex representation of the input, but can lead to overfitting. Few neurons simplify the model reducing the risk of overfitting, but can lead to underfitting. 
- Good to start with small number (256 or 512), and gradually increase the number of neurons in each layer until diminishing returns in term of accuracy and loss. 

Question 3 - What are the metrics to use to evaluate the performance of a machine learning model?
- **Precision**: Proportion of true positive predictions out of all positive predictions. Measure the proportion of relevant instances among the retrieved instances. 
- **Recall**: Proportion of true positive predictions out of all actual positive instances. Measure the proportion of the total amount of relevant instances that were actually retrieved.

Question 4 - Why are data divided in 3 parts - Training, Validation, Testing? 

Allow to get a more realistic estimate of the model's performance on new, unseen data. Help with preventing overfitting and underfitting of the model.
- **Training Set**: Training set is used to train the model. Present the model with input-output pairs and adjust the model's parameters to minimise the error on the training set. 
- **Validation Set**: Use to evaluate the **model's performance during the training process and to tune the hyperparameters of the model**. Allow to check for overfitting or underfitting. Compare the performance of the model on the training and validation set to identify when the model has learned underlying patterns in the training data but not yet memorised the data (ie. the sweet spot). 
- **Testing Set**: Use to evaluate the **final performance of the model** after it has been trained and fine-tuned. Use to estimate the error of the model on new, unseen data. 
