# deep-learning-challenge_

Results Overview of the analysis: - The purpose of the analysis was that the nonprofit foundation Alphabet Soup wanted a tool that can help select the applicants for funding with the best chance of success in their ventures. Machine learning and neural networks were used to create a binary classifier which could predict whether applicants will be successful if funded by Alphabet Soup. From Alphabet Soup’s business team, a CSV was recieved containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.

1. Data Preprocessing •Target variable : IS_SUCCESSFUL. •Feature variable : APPLICATION_TYPE AFFILIATION CLASSIFICATION USE_CASE ORGANIZATION STATUS INCOME_AMT SPECIAL_CONSIDERATIONS ASK_AMT • the variables that were removed were indentification columns EIN and NAME

2. Compiling, Training and Evaluating the Model

•In the step 2 for compiling training and evaluating the model , the first model new neuron were assigned other than 80 and 30 , used 9 and 18 neuron splits with having 2 hidden layer and 1 activation layer . The activation layer was on 'relu' with 'sigmoid' on the output layer . The results were 73% which is lower than the target set i.e 75%.

Optimizing the model The model was optimized with the help of adding a new layer with neuron = 27 other changes that were applied were that instaed of removing the name column, it was used as afeature and binned together. The classification_type was also kept as a feature. This resulted in 78% accuracy. which was more than the set target.

Summary The target accuracy of 75% was reached with adjusting the layers in the model even though the target accuracy was achievied ,different models like RandomForest can provide with numerous intrepretation when realted to combining the decision tree with efficient performance whereas tensorFlow requires more data and depends on the variables.
