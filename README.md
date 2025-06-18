Project Title: Legal and Product Text Summarization with LoRA-enhanced Transformers
Overview
This project demonstrates two fine-tuning pipelines for abstractive text summarization using HuggingFace Transformers and the LoRA (Low-Rank Adaptation) technique for efficient training.

It includes:

Legal Document Summarization

Uses the google/flan-t5-base model.

Trained on the legal_summarizer_data dataset from HuggingFace.

Incorporates LoRA to reduce memory usage while maintaining accuracy.

Product Search Summarization (Query → Title)

Trains on a custom dataset of search queries and product titles.

Reformulates search terms into more relevant product descriptions.

Technologies Used
Transformers (google/flan-t5-base)

HuggingFace Datasets

PEFT (Parameter-Efficient Fine-Tuning)

LoRA

PyTorch

Google Colab

Key Features
Efficient training with LoRA.

Text summarization tuned for legal and e-commerce domains.

Dataset filtering and preprocessing included.

Export-ready tokenizer and model.

