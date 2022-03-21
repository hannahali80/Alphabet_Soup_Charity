# Alphabet_Soup_Charity Analysis:


**The purpose of this analysis is well defined **

-To use neural network to test and train model.

-The data is pre-processed to ensure it in good working condition before applying the model

-The model is optimized and results are evaluated

-Adjustment made in order to make the accuracy rate 75% or more. 
 
**Data Preprocessing**

What variable(s) are considered the target(s) for your model?

The IS_SUCCESSFUL column is the target of model. 

What variable(s) are considered to be the features for your model?

All columns are considered variable other than IS_SUCCESSFUL.

What variable(s) are neither targets nor features, and should be removed from the input data?

The two that were removed initially was EIN & NAME that were neither targets nor features.

**Compiling, Training, and Evaluating the Model**

How many neurons, layers, and activation functions did you select for your neural network model, and why?

Two layers were selected and the activation chosen was relu as it best produce accuracy result.

Were you able to achieve the target model performance?

Overall I was able to achieve 69%. I tried to increase the units and add more layers to see if model will accuracy but it did not.

What steps did you take to try and increase model performance?

I tried to first add more layer and increase the units. I also tried changing the activation type but did not affect the performance rather it decreased it.


**Summary**

The model after optimization resulted in 66% accuracy while initially the model has 69% accuracy. From both the results it looked like the model was over fitted and perhaps this is the reason for more loss.  Other models could be explored to see if the accuracy is better such as using Random Forest Clusters. Overall a good project to see how accuracy changes and it could take trial and error to produce better models
