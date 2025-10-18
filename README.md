# Automatic-Fact-Checking-of-Arabic-Claims-
Introduction
This project focuses on automated Arabic fact-checking using a comprehensive dataset of over 18,500 Arabic claims, labeled with categories such as True, False, Partly-False, Sarcasm, and Unverifiable. Our goal is to build models that can automatically classify these claims based on their factual accuracy. To achieve this, we explore and compare three different approaches:

BERT with Manual Preprocessing: We fine-tune the BERT model using Arabic text that we preprocess manually to handle challenges like diacritics and character encoding.
BERT with CAMeL Tools Preprocessing: Here, we use CAMeL Tools, a set of Arabic NLP tools, to preprocess the text before feeding it into BERT. This automates tasks like normalization and tokenization, which could improve performance.
AraBERT with CAMeL Tools Preprocessing: AraBERT is a version of BERT specifically trained on Arabic text. We combine it with CAMeL Tools to see if a model designed for Arabic, paired with advanced preprocessing, performs better than standard BERT.
We also create an interactive interface using Gradio, allowing users to input Arabic claims and get real-time predictions on their accuracy. This makes the model easy to use and accessible. By comparing these three methods, we aim to find the best approach for Arabic fact-checking while tackling challenges like Arabic’s complex grammar and character encoding.


Conclusions
A pre-trained converter (BERT) was used in this project to effectively create an Arabic text classification model. Normalization methods were used for preprocessing the dataset, and then named data was used to refine the model. The model works well, according to the evaluation criteria, which include accuracy, accuracy, recall and F1 grade.
More information about erroneous classifications is provided via the Confusion Matrix view. With possible extensions of applications such as sentiment analysis and topic categorization, this method demonstrates the value of using deep learning models for natural Arabic language processing tasks.

Taem members: Reema Alghannam - Sara Alayban.



















