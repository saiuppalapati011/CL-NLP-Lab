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

---

## 🛠 Setup & Installation

To run these experiments locally on your machine, you'll need Python installed along with Jupyter and standard Data Science/NLP libraries.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/saiuppalapati011/CL-NLP-Lab.git
   cd CL-NLP-Lab
   ```

2. **Install required dependencies:**
   *(Note: Ensure you have libraries like `pandas`, `nltk`, `spacy`, or `scikit-learn` installed depending on the specific experiment's requirements).*
   ```bash
   pip install jupyter pandas nltk scikit-learn
   ```

3. **Run Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

---
*Created and maintained by Sai Uppalapati.*
