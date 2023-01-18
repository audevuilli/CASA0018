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
