# GPT2-Persian-Poetry

**Dataset Creation**

This repository provides a preprocessed dataset of Persian poetry, derived from a collection of Persian poems on GitHub. The dataset has been carefully curated and formatted to facilitate natural language processing tasks.

**Data Preprocessing**

* **Tokenization:** The text has been tokenized by [HooshvareLab/gpt2-fa-poetry](https://huggingface.co/HooshvareLab/gpt2-fa-poetry) to prepare it for model training.
* **Special Tokens:** To enhance the model's ability to understand the structure of Persian poetry, we have added special beginning-of-verse (BOM) and end-of-couplet (EOS) tokens. These tokens help the model recognize the boundaries of poetic units.

**Model Fine-tuning**

A pre-trained GPT-2 model [HooshvareLab/gpt2-fa-poetry](https://huggingface.co/HooshvareLab/gpt2-fa-poetry) has been fine-tuned on this dataset to generate high-quality Persian poetry. The fine-tuning process involved:

* Using the provided tokenizer to convert the text into numerical representations.
* Training the model on the tokenized dataset, allowing it to learn the patterns and nuances of Persian poetry.

**Dataset Sources**
  [Bolbolzaban](https://github.com/khashei/bolbolzaban-gpt2-persian)
  
  [Persian_poems_corpus](https://github.com/amnghd/Persian_poems_corpus/tree/master)

