# Computational Linguistics - Natural Language Processing (CL-NLP) Lab

Welcome to the CL-NLP Lab repository! This repository contains a collection of experiments and practical implementations for Natural Language Processing, developed as part of the coursework. 

Each experiment focuses on a specific aspect of NLP, ranging from basic text processing to advanced techniques like Named Entity Recognition (NER) and Term Frequency analysis. All implementations are provided in Jupyter Notebooks with corresponding datasets and detailed documentation.

---

## 📁 Repository Structure and Experiments

### [Experiment 1: Introduction to Data Processing](./Experiment%20-%201)
This experiment covers the foundational steps of data loading and initial processing.
- **`Experiment 1.ipynb`**: Core implementation notebook.
- **`employee_information_100.csv`**: Sample dataset containing employee records used for data manipulation.
- **`Experiment-1.docx`**: Detailed report containing methodology, code explanations, and outputs.

### [Experiment 2: Text Tokenization and Cleaning](./Experiment%20-%202)
Focuses on the critical preprocessing steps in NLP: breaking text into tokens and cleaning noisy data.
- **`Experiment - 2.ipynb`**: Jupyter notebook demonstrating various tokenization and cleaning techniques.
- **Datasets**: 
  - `2.1_text_data.txt`: Raw text input.
  - `2.2_tokenization_data.txt`: Intermediate tokenized output.
  - `2.3_clean_data.txt`: Final cleaned text dataset.
- **`Experimemt-2.docx`**: Comprehensive report of the experiment's findings and pipeline.

### [Experiment 3: Advanced NLP Techniques](./Experiment%20-%203)
Builds upon previous experiments to implement more advanced linguistic computations.
- **`Experiment 3.ipynb`**: Implementation notebook.
- **`Experiment-3.docx`**: Extensive documentation and analysis report of the techniques applied.

### [Experiment 4: Term Frequency and Named Entity Recognition (NER)](./Experiment%20-%204)
Explores information extraction techniques by calculating term frequencies and identifying named entities within a text.
- **`Experiment - 4.ipynb`**: Notebook covering TF calculations and NER implementations.
- **Datasets**:
  - `4.1_4.2_input.txt`: Raw text corpus for analysis.
  - `term_frequency.csv`: Extracted term frequencies from the corpus.
- **` Experiment-4_ Term Frequency and NER.docx`**: Detailed breakdown of the algorithms used, including results and insights.

### [Experiment 5: Subword Tokenization and Part-of-Speech (POS) Tagging](./Experiment%20%20-%205)
Explores subword segmentation algorithms (Byte Pair Encoding, SentencePiece) and syntactic Part-of-Speech (POS) tagging.
- **`Experiment_5.ipynb`**: Implementation notebook demonstrating pretrained & custom BPE, SentencePiece tokenization, and POS tagging.
- **`Experiment_5_Current_Environment.ipynb`**: Environment-specific notebook with kernel dependency checks and verified execution.
- **Datasets & Model Artifacts**:
  - `input_sub_word_data.txt`: Text corpus used for tokenization and model training.
  - `my_bpe.model` & `my_bpe.vocab`: Trained SentencePiece BPE model and vocabulary files.
- **`Experiment-5.docx`**: Comprehensive report covering methodology, algorithm comparisons, and tag distributions.

### [Experiment 6: GloVe Word Embeddings and Statistical N-gram Language Model](./Experiment%20-%206)
Implements word embeddings with GloVe (both from scratch and pretrained) and a statistical N-gram language model from scratch for next-word prediction.
- **`Experiment - 6.ipynb`**: Implementation notebook covering custom AdaGrad GloVe, pretrained Gensim GloVe (`glove-wiki-gigaword-50`), and Unigram/Bigram/Trigram next-word prediction with backoff.
- **Datasets**:
  - `glove_corpus.txt`: Text corpus used to train GloVe embeddings from scratch.
- **`Experiment-6.docx`**: Experiment problem statement and reference corpus.

### [Experiment 7: Sentiment Analysis on IMDB Movie Reviews](./Experiment%20-%207)
Implements and compares four sentiment classification approaches on the 50K IMDB Movie Reviews dataset using Accuracy, Precision, Recall, F1-Score, and Confusion Matrices.
- **`Experiment - 7.ipynb`**: Implementation notebook comparing TF-IDF + Logistic Regression, Bidirectional LSTM, Vanilla Transformer Encoder, and Pretrained BERT (`textattack/bert-base-uncased-imdb`).
- **`Experiment-7.docx`**: Experiment specification and dataset links.

### [Experiment 8: Multilingual Abstractive Text Summarization (mT5 vs. mBART)](./Experiment%20-%208)
Implements and evaluates multilingual abstractive summarization on the Hindi split of the XL-Sum dataset using ROUGE-1, ROUGE-2, ROUGE-L, and mBERTScore.
- **`Experiment - 8.ipynb`**: Implementation notebook comparing `Anshugh/mt5-small-hindi-xlsum` (mT5) and `ai4bharat/IndicBART-XLSum` (mBART) with Unicode-aware ROUGE and `bert-base-multilingual-cased` BERTScore.
- **`Experiment-8.docx`**: Experiment specification and XL-Sum dataset reference.

---

## 🛠 Setup & Installation

To run these experiments locally on your machine, you'll need Python installed along with Jupyter and standard Data Science/NLP libraries.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/saiuppalapati011/CL-NLP-Lab.git
   cd CL-NLP-Lab
   ```

2. **Install required dependencies:**
   *(Note: Ensure you have libraries like `numpy`, `pandas`, `nltk`, `spacy`, `gensim`, `torch`, `transformers`, `datasets`, `rouge-score`, `bert-score`, or `sentencepiece` installed depending on the specific experiment's requirements).*
   ```bash
   pip install jupyter numpy pandas matplotlib nltk scikit-learn torch transformers datasets rouge-score bert-score sentencepiece spacy gensim
   python -m spacy download en_core_web_sm
   ```

3. **Run Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

---
*Created and maintained by Sai Uppalapati.*
