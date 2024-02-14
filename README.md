# deep-learning-challenge
Module 21

Purpose of the Analysis: 
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. The CSV file contained more than 34,000 organizations that have received funding from Alphabet Soup over the years. 

Data Processing :

• The target variable is 'IS SUCCESSFUL'.
• The featured variables in the model are :
   EIN
   Name
   Application_TYpe
   Affiliation
   Classification
   Use_Case
   Organization
   Status
   Income_Amt
   Special_Considerations
   Ask_Amt
   Is_Successful
• EIN and Name were removed from the input data because they are neither targets nor features.
 
Compiling, Training, and Evaluating the Model :

• How many neurons, layers, and activation functions did you select for your neural network model, and why?
  There were two layers :
  Layer1 = 8 hidden_nodes and Layer2 = 5 hidden_nodes

• Were you able to achieve the target model performance? No

• What steps did you take in your attempts to increase model performance? I added additional layer to increase model performance.

Summary : 
The deep learning model was around 73% accurate. I believe to improve accuracy of classification model the following can be performed: add more data, feature engineering, feature selection, multiple algorithms, and cross validation. There could be some more approaches.





