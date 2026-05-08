# NLP Complaint Analysis

## Project Description
This project analyzes unstructured complaint texts using Natural Language Processing (NLP) techniques in Python. The goal is to identify the most prevalent topics discussed in customer complaints.

The project uses the Comcast Telecom Complaints Dataset from Kaggle as a proxy dataset for complaint analysis.

## Methods Used
- Text preprocessing with NLTK
- Bag-of-Words (CountVectorizer)
- TF-IDF vectorization
- Latent Semantic Analysis (LSA)
- Latent Dirichlet Allocation (LDA)

## Technologies
- Python
- pandas
- NLTK
- scikit-learn
- matplotlib

## Project Structure

```text
data/           -> dataset files
notebooks/      -> Jupyter notebooks
results/        -> generated outputs/results
src/            -> optional Python scripts
```

## Environment Setup

```bash
conda env create -f environment.yml
conda activate nlp-topic-modeling
```

## Running the Project

Open `main.ipynb` in VS Code and select the `nlp-topic-modeling` kernel.

## Dataset
Comcast Telecom Complaints Dataset (Kaggle)

## Author
GitHub: 9224365