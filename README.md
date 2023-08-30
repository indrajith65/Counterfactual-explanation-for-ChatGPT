# Counterfactual-explanation-for-ChatGPT
This project's objective is to understand the words selected for an GPT input to get a high related response from the transformer model. GPT-2 transformer is used to generate 3 responses for an input prompt, then the best related response is selected among the three. Based on the obtained probabilty, a threshold was set and the highest probabilty along with the tokenized words were encoded into a dataframe. After categorizing the target variable, diverse counterfactuals are obtained for the dataframe using dice_ml

# Visualization 
The dataframe is visualized in logarithmic graph and the diverse counterfactual explanations are produced.

# Installation 
The libraries can be installed via pip.

!pip install transformers
!pip install dice_ml
