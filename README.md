# Sarcasm News Detection Using Roberta-Base

Here, I would like to solve a sentence classification problem. The model will classify a given sentence as sarcastic or non-sarcastic. Here, the sentence is a news headline.

Example 1: California court rules bees are now fish - sarcastic

Example 2: God getting a strong urge to bring back dinosaurs - sarcastic

Example 3: 10 essential life lessons from a grandma - non-sarcastic

I was very interested in doing a project with sentiment analysis. So, I was looking for a problem in this domain. While I was searching for a dataset, I came across a dataset for sarcasm news headline detection. I decided to work with this dataset as it seemed exciting, and it is something I have never encountered before.

# Dataset Link: 
https://huggingface.co/datasets/raquiba/Sarcasm_News_Headline

I have used an encoder-only ‘roberta-base’ model. I have experimented with a couple of models, such as bert-base, etc. I have received better results with roberta-base model. Also, I have read some research papers which are claiming that ‘roberta-base’ model performs better than others for this kind of problems. So, I was curious to see how it performs.

# Model Overall Quantitative Performance Measure: 
{'accuracy': 0.9871637161041878}, {'f1': 0.9853049228508449}




