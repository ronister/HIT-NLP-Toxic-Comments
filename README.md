# HIT-NLP-Toxic-Comments
HIT - NLP Project - Toxic Comments text classification using BERT, SpaCy and Sklearn and PyTorch

The research question and objective of this project is, whether we can classify toxic comments that appear in Wikipedia Talk Pages (aka. “discussion pages”) with a reasonably high accuracy.

The Dataset is taken from Kaggle competition  held 5 years ago. 
It contains approximately 160K rows, with 8 columns: ‘id’, ‘comment_text’  and 6 types of toxicity target labels (1/0), which have been labeled by human raters of toxic behavior:
![image](https://github.com/ronister/HIT-NLP-Toxic-Comments/assets/30979104/6414f381-f704-44ae-bc5b-8b25a2fd9ca7)

Toxic – Very bad, unpleasant, harmful.
Severe toxic – Extremely bad and offensive.
Obscene – Description of sexual matters.
Threat –  a statement of an intention to inflict pain, injury, or damage.
Insult – speak to or treat with disrespect or scornful abuse.
Identity hate – hatred, hostility, or violence towards ethnicity, nation, religion, gender. 

Type of NLP Challenge: Text classification - A task of categorizing text documents into predefined classes or categories. It is a fundamental problem in NLP with various applications, such as:

1. Sentiment Analysis: Determine the sentiment expressed in a text as positive, negative, or neutral. 
2. Spam Detection (in emails)
3. Topic Categorization: Classify news into categories such as sports, politics, entertainment, or  technology.
4. Intent Recognition: Identify the intent or purpose behind a user's query or statement.
    (e.g., classify customer queries in a Chatbot as inquiries, complaints, or requests for assistance).
5. Named Entity Recognition (NER) (e.g., Identify and classify person names, locations, organizations).
6. Language Identification (e.g., English, Spanish, or French).

Motivation:
- A lot of websites run on user generated content and are dependent on user discussions to curate and approve content.
- People frequently write toxic, inappropriate or offensive things they shouldn’t, and to maintain a positive community this content and the users posting it need to be removed quickly.
- Hiring full-time moderators to review every comment is expensive.





