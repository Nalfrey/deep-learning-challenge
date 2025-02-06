# deep-learning-challenge
**OVERVIEW**
Utilizing a charity data csv I took the data to create a tool to help "Alphabet Soup" select applicants for funding with the best chance of success in their ventures. 
First I preprocessed the data using Pandas and scikit-learn to compile, train, and evaluate the neural network model. Using Google Colab the data was scrubbed and combined to create a data set for training and testing using a Standard scaler instance. 
After that a binary classification model was created to predict if an Alphabet Soup funded organization will be successful based on the features that were kept in the dataset. 
Lastly the model was optimized to ensure that there were no variables or outliers that would cause confusion in the model. 

**RESULTS**
**Data Preprocessing**

What variable(s) are the target(s) for your model? The target is "IS_SUCCESSFUL"
What variable(s) are the features for your model? APPLICATION_TYPE,AFFILIATION,CLASSIFICATION,USE_CASE,ORGANIZATION,STATUS,INCOME_AMT,SPECIAL_CONSIDERATIONS,ASK_AMT,IS_SUCCESSFUL
What variable(s) should be removed from the input data because they are neither targets nor features?  EIN,NAME

**Compiling, Training, and Evaluating the Model**

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance

**sUMMARY**
