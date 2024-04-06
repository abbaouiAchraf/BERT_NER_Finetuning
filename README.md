# BERT Named Entity Recognition with CoNLL-2003 Dataset

This repository showcases the process of fine-tuning the BERT base uncased model for the Named Entity Recognition (NER) task using the CoNLL-2003 dataset on Hugging Face.

## Table of Contents

- [Project Description](#project-description)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Project Description

Named Entity Recognition (NER) is a crucial task in Natural Language Processing (NLP) that involves identifying and classifying named entities (e.g., persons, organizations, locations) within text data. This project demonstrates how to fine-tune the pre-trained BERT base uncased model for the NER task using the CoNLL-2003 dataset.

The CoNLL-2003 dataset is a widely used benchmark dataset for the NER task, consisting of news articles from the Reuters Corpus. The dataset is annotated with four entity types: Person (PER), Organization (ORG), Location (LOC), and Miscellaneous (MISC).

## Installation

1. Clone the repository:

```bash
git clone https://github.com/abbaouiAchraf/BERT-NER-COLL2003.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter Notebook `bert-ner-finetuning.ipynb`.

2. Follow the step-by-step instructions provided in the notebook to:
   - Load and preprocess the CoNLL-2003 dataset
   - Set up the BERT model and tokenizer
   - Define the data loaders and the training/evaluation loop
   - Fine-tune the BERT model
   - Evaluate the model's performance
   - Make predictions on new text data

3. The notebook includes detailed explanations and code snippets to guide you through the entire process.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

To contribute, follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Make your changes and commit them (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Open a Pull Request
