# Neural_Network_Charity_Analysis

## Overview of the analysis: 
  The purpose of this analysis was to use a machine learning model to determine which charity's application would be successful. Once the model was run, different methods were used to optimize the model to increase the accuracy of its predictions. One method entailed updating the exisiting deep neural model by increasing the number of nodes and hidden layers. The other method entailed using a neural network model to compare to the accuracy of the deep neural model and then afterwards, adding epochs to the neural network model after running the inital model.

## Results
* The target variable for the model was the charities which had successful applications. 
* Features of the model were charity application type, charity affiliation, purpose of the charity, type of organization, organization status, organization income amount, special considerations, and organization asking amount.  
* The name of the organization and the EIN for each organization were neither targets nor features, and were therefore removed from the input data.
* In the initial deep neural model, there were 80 neurons and 2 layers, and the activation function was OneHotEncoder. These features were selected for the neural network model due to...
* I was not able to achieve the target model performance of above 75% with my first attempt, and only achieved 69.7% accuracy. I then attempted to optimize my model by increasing the initial number of nodes in the first layer from 80 to 100 and the number of nodes in the second layer from 30 to 50. I also added a third layer with 25 nodes. This resulted in a decrease in accuracy of the model down to 41.4%. 
* Unhappy with my first attempt to optimize the model, I also tried using a neural network model which called back the model's weight every 5 epochs, using 100 epochs. This resulted in a model with increased accuracy from both the inital model and the first optimized model, with an accuracy of 72.5%.
* I tried a third time to optimize the data, this time using the neural network model again. In this go-round, I increased the number of epochs to 150. The resulting accuracy was 72.5%. 
## Summary: 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
