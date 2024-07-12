# ner-chatbot-transformer
Chatbot using Named Entity Recognition via HuggingFace

Project Overview:
Given an order via a phone call, use a transformer applied towards a NER Task that will allow the model to extract and label the following:
- item [ITEM]
- item quantity [QTY]
- item deliver location [LOC]
- date for item to be delivered by [DATE]
- specific time window for item to be delivered during [TIME]

The client making the order won't need to be included as the main objective is to gather the info above to make an order. Therefore, this project is under the assumption that the client id is known when making a order. 

- Convert audio into text (Not in curren version)
- tokenize text into words and subwords (Tokenizer)
- padding and truncating
- FT model (HF)
    - Create Training Arguements
    - Create a Trainer Class
    - Train Model
    - Evaluate Model
    - Make predictions 
    - Upload to HF Model Hub





Resources (links below):

- https://www.geeksforgeeks.org/named-entity-recognition/

- https://huggingface.co/transformers/v3.0.2/quicktour.html

- https://huggingface.co/transformers/v3.0.2/task_summary.html

- https://huggingface.co/transformers/v3.5.1/main_classes/pipelines.html

- https://www.reddit.com/r/LanguageTechnology/comments/lnca2q/some_questions_about_spacy_vs_hugging_face/