# Spell Checker using BERT Tokenizer

This project implements a **spell checker** that preprocesses text, removes stopwords, and applies deep learning-based tokenization using the **BERT tokenizer**.

## Features
- **Text Tokenization:** Uses BERT tokenizer to process text efficiently.
- **Stopword Removal:** Filters out unnecessary words using NLTK.
- **Stemming:** Applies **Porter Stemmer** to reduce words to their base forms.
- **Dataset Handling:** Uses pandas and datasets library for text processing.
- **Deep Learning Integration:** Utilizes PyTorch and Transformers.

## Technologies Used
- **NLTK** (Stopwords, Porter Stemmer)
- **Transformers** (BERT Tokenizer)
- **Pandas** (Data handling)
- **Torch** (Deep Learning framework)
- **Datasets** (For NLP datasets)

## Installation
Install the required dependencies:
```bash
pip install pandas nltk torch transformers datasets
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/yourusername/Spell-Checker.git
cd Spell-Checker
```
2. Run the Jupyter Notebook:
```bash
jupyter notebook Spell_Checker.ipynb
```
3. Follow the notebook instructions to preprocess text, clean data, and apply spell checking.

## Example Output
- **Input:** "Ths is a smple txt wth erors."
- **Output:** "This is a simple text with errors."

## Contributing
Feel free to submit issues or pull requests to improve this project.


