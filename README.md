# Document Similarity

A Python-based model that analyzes and compares the similarity between two documents using TF-IDF vectorization, Cosine Similarity, and Logistic Regression.

## 📝 Description

This project implements a document similarity detection system that:
- Compares two documents and calculates their similarity score
- Identifies and displays matching text segments between documents
- Uses advanced NLP techniques including TF-IDF vectorization
- Employs Logistic Regression for accurate similarity classification
- Supports multiple document formats (.docx, .pdf)

## 🚀 Features

- Document pair comparison
- Sentence-level similarity detection
- Similarity score calculation
- Support for Microsoft Word (.docx) and PDF files
- Interactive Google Colab implementation

## 📊 Dataset

The model is trained on the Microsoft Research Paraphrase Corpus (MRPC), which includes:
- `msr_paraphrase_train.txt`: Training dataset
- `msr_paraphrase_test.txt`: Testing dataset

## 🛠️ Installation

### Required Files
1. `DocumentSimilarity.ipynb`: Main project notebook
2. `msr_paraphrase_train.txt`: Training dataset
3. `msr_paraphrase_test.txt`: Testing dataset

### Setup Instructions

1. Download all required files
2. Open Google Colab
3. Upload `DocumentSimilarity.ipynb` to Colab
4. Follow the notebook instructions in sequence

## 💻 Usage

1. Run all preliminary code sections
2. When you reach the "Upload dataset" section:

<img width="539" alt="Image" src="https://github.com/user-attachments/assets/4de1f6f0-7b11-4235-ba37-0898f655b02c" />

3. Continue executing the notebook
4. At the "Process and compare" section:
   - Upload any two documents (.docx or .pdf) you want to compare
   - The model will process them and display:
     - Overall document similarity score
     - Matching sentence pairs
     - Similarity scores for each pair

## 📋 Example Output

<img width="467" alt="Image" src="https://github.com/user-attachments/assets/1dd25aca-4c37-4217-89c9-03a8de2b5f26" />

## 🧮 Technical Implementation

The project uses several key technologies:
- TF-IDF (Term Frequency-Inverse Document Frequency) vectorization for text representation
- Cosine Similarity measurement for vector comparison
- Logistic Regression for similarity classification
- Python's natural language processing libraries

## 📥 Dataset Format

The training dataset includes:
```
Quality    #1 ID    #2 ID
1          702876   702977
0          2108705  2108831
1          1330381  1330521
0          3344667  3344648
1          1236820  1236712
```

## ⚖️ License

[Include your license information here]

## 👥 Contributors

[Add contributor information here]

## 📫 Contact

[Add contact information here]
