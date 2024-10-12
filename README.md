# English to Arabic Translation using MarianMT

This project demonstrates fine-tuning the MarianMT transformer model for English-to-Arabic translation. MarianMT is a multilingual translation model designed for efficient machine translation tasks.

## Model and Dataset
- Model: MarianMT (a pre-trained transformer model specialized in translation tasks).
- Dataset: A parallel corpus of English-Arabic sentence pairs used to fine-tune the translation model.

## Task
The task is to translate English sentences into Arabic, leveraging a pre-trained model and fine-tuning it on a high-quality dataset for better performance in the English-Arabic language pair.

## Workflow
1. Preprocessing: English and Arabic sentences are tokenized and prepared for input to the MarianMT model.
2. Fine-tuning: The MarianMT model is fine-tuned on the parallel corpus to enhance translation accuracy specifically for the English-Arabic pair.
3. Evaluation: The model is evaluated using BLEU score and other relevant translation metrics.

## Usage
To use this notebook:
1. Clone the repository and install the required dependencies.
2. Run the notebook to fine-tune the MarianMT model on English-Arabic translation.
3. Use the fine-tuned model to translate English texts to Arabic.
