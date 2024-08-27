# deep-learning-challenge
Module 21 challenge

In the Folder:
1. "Starter_code_hw.ipynb" is the completed homework file for the challenge's steps 1 and 2
2. "AlphabetSoupCharity.h5" is the file taht was exported from the "Starter_code_hw.ipynb" file
3. "AlphabetSoupCharity_optimization.ipynb" and "AlphabetSoupCharity_optimization.h5" are the completed homework files for the challenge's step 3
4. "Starter_code.ipynb" was the provided file kept for reference.
5. Below is the report for setp 4





Overview of the analysis: Explain the purpose of this analysis.
    The purpose of the analysis was to crate a neural network model that would select applicants for funding for the best chance of success in their ventures

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
    Our target variable for the model is y which the guided homework assigned to the column "IS SUCCESSFUL".
What variable(s) are the features for your model?
    For the features of the model, x which the guided homework assigned to all the columns except for "IS SUCCESSFUL".
What variable(s) should be removed from the input data because they are neither targets nor features? 
    The variables "EIN" and "NAME" were revoed from the input data as they are neither targets nor features.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why? 
    For the guided homework file I chose 80 and 30 neurons and 2 layers to match the answer key. For my optimization I chose to do 4 layers and went from 100,50,25,10, down to 1 neurons as from what I understood the more layers and neurons you have the better the deep learning would have a higher chance of higher accuracy. 
Were you able to achieve the target model performance?
    My optimization showed 73.0% accuracy compared to the 72.8% accuracy from the guided homework file.
What steps did you take in your attempts to increase model performance?
    I tried including more Application Types as well as more Classifications to widen the possibilities when sliptting the processed data as well has changing from 2 layers to 3 and eventually 4 layers in the final saved file. 

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
    The deep learning model was able to achieve a 73.0% accuracy which seems reasonable, however there is definitely room for improvement. I'd recommend other models we've learned in the previous section like the Random Forests or even Decision Trees that taken in a number of features to help classify and maybe narrow down the data prior to entering it into this deep learning model.
