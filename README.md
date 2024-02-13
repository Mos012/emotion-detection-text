in this project we use roberta pretrained model with POS and Dependency parsing tags to create a model for detecting emotions on isear dataset.
In the first part, pre-processing is done on the text. In the next part, each word in the input text is replaced with its equivalent  POS and dependency parsing tags, and it is added as an additional feature to the features extracted from Roberta model.
The first model is Roberta with POS and the second model is Roberta with dependency.
​
