# Creating AI for predictions in databases

# step 0 - understand the company needs

# step 1 - import database
    # verify if there is any error on the database created
    # display(tablecreated.info())
    
# step 2 - preparing the database for the AI
    # AI only learns number not text (pre processing transforming text into numbers to AI)
    # the only colums that should be text is the one you are looking for predictions
    # divide the database in four (two training & two tests) (what you want to predict and what column you will use for the prediction)
    # remove the columns that do not needs to be used (id_clientes is a random numbers, so we will exclude it for what we need in our code)
        # x = who the AI can use to make the prediction
        # y = who the AI must predict
    # training AI to learn 
    # Kaggle website as exemple to use 

# step 3 - creating AI (always apply 3 steps)
# 1 - import the AI
# 2 - create the AI
# 3 - training the AI

# step 4 - choosing the best model

# step 5 - using our model to make predictions
