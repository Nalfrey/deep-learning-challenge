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

How many neurons, layers, and activation functions did you select for your neural network model, and why? I honestly could not get this portion of my code to work. I thought I had the code wrong, continued to edit, but had spent many iterations trying to get it to work with iterations I had. 

Were you able to achieve the target model performance? No, because I couldn't get the model to work as intended. 

What steps did you take in your attempts to increase model performance? I took multiple steps, multiple changes but ultimately to increase you would add layers from 2, to 4, to 6, to 8 etc etc and change the neurons from a small number such as 10 or 20 and increase to 200 or 500. 

**sUMMARY**
In summary, neural networks are difficult, and I couldn't get this model to work as I had intended without my computer RAM running out. 
