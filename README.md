# Counterfactual-explanation-for-ChatGPT
This project's objective is to understand the words selected for an GPT input to get a high related response from the transformer model. GPT-2 transformer is used to generate 3 responses for an input prompt, then the best related response is selected among the three. Based on the obtained probabilty, a threshold was set and the highest probabilty along with the tokenized words were encoded into a dataframe. After categorizing the target variable, diverse counterfactuals are obtained for the dataframe using dice_ml

## What is DiCE?
![image](https://github.com/indrajith65/Counterfactual-explanation-for-ChatGPT/assets/42492107/102c3ede-ee59-442e-9777-327cd8186e4f)
DiCE (Diverse Counterfactual Explanation) is used as a means to demonstrate the various approaches by which a comparable result can be attained. The DiCE library facilitates the comprehension of a machine learning model by generating alternative feature values, commonly referred to as "what-if" scenarios. 

## Visualization 
The dataframe is visualized in logarithmic graph and the diverse counterfactual explanations are produced.
![image](https://github.com/indrajith65/Counterfactual-explanation-for-ChatGPT/assets/42492107/ffef5c87-a4f3-4af3-a7d3-2ce88560949e)


## Installation 
The libraries that were used in this project can be installed as below.
```
pip install transformers dice_ml
```
## Output

The tested counterfactual explanation can be seen from the below image
![image](https://github.com/indrajith65/Counterfactual-explanation-for-ChatGPT/assets/42492107/536a27f0-489e-4cad-b5aa-056f7f86acb0)

