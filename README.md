This project uses the transformers library by Hugging Face to build an automated Question-Answering (QA) system. It takes in a list of text passages, generates questions, filters for unique questions only, and answers them using a fine-tuned transformer model (deepset/roberta-base-squad2).

📌 Features
Uses the deepset/roberta-base-squad2 model for high-quality extractive QA

Automatically generates questions from input text

Filters to ensure each question is answered only once

Answers questions for the first 5 passages only

Modular design for flexibility and reuse
