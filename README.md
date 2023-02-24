# BERT_Spam_Detection

This project aims to fine-tune BERT model to detect spam SMS using [SMS Spam Collection](https://www.kaggle.com/uciml/sms-spam-collection-dataset). The dataset consist of 5,574 English SMS which tagged accroding ham or spam.

# BERT
BERT is designed to help computers understand the meaning of ambiguous language in text by using surrounding text to establish context.
<br>
Using HuggingFace to fine tune `bert-base-model`, the following result is achieved.

![image](/assets/loss_graph.PNG)

The classification report is:
<br>
![image](/assets/classification_report.PNG)