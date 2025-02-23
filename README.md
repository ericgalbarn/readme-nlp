# Document Similarity

A Python-based model that identifies and calculates similarities between documents using NLP techniques. The model employs TF-IDF vectorization, Cosine Similarity calculations, and Logistic Regression to determine textual similarities between document pairs.

## Overview

This project implements a document similarity detection system that can:
- Compare two documents (.docx or .pdf format)
- Calculate similarity scores between documents
- Identify and display matching text passages
- Use machine learning to classify similar sentence pairs

## Technologies Used

- Python
- TF-IDF Vectorization
- Cosine Similarity
- Logistic Regression
- Google Colab (recommended environment)

## Dataset

The model is trained on the Microsoft Research Paraphrase Corpus (MRPC), which includes:
- `msr_paraphrase_train.txt`: Training dataset
- `msr_paraphrase_test.txt`: Testing dataset

## Installation and Setup

1. Download the required files:
   - `DocumentSimilarity.ipynb` (source code)
   - `msr_paraphrase_train.txt` (training dataset)
   - `msr_paraphrase_test.txt` (testing dataset)

2. Upload the `DocumentSimilarity.ipynb` to Google Colab

3. Follow the notebook instructions in sequence:
   - Run each code cell in order
   - When you reach the section `# 2. Upload dataset`, upload both MRPC dataset files
   - Continue executing the remaining cells

## Usage

1. Run all cells up to the section `# 8. Process and compare`
2. At this point, you can upload any two documents (.docx or .pdf) from your computer
3. The model will:
   - Calculate and display the similarity score between the documents
   - Show matching sentence pairs between the documents

## Example Output

![Document Similarity Interface](path_to_image_1.png)
![Similarity Results](path_to_image_2.png)

## Contact

[Add your contact information or project maintainer details here]

## License

[Add your license information here]
