# Climate Sentiment Classification & Topic Discovery

This project focuses on analyzing corporate disclosures for climate-related sentiment — classifying texts as **risks**, **opportunities**, or **neutral** — using multiple machine learning methods. It also explores unsupervised topic discovery to identify key themes associated with risks and opportunities.

## 🚀 Key Features

- **Sentiment Classification**:
  - Naïve Bayes (Bag-of-Words, TF-IDF, Bigrams)
  - Feed-Forward Neural Network (PyTorch)
  - ClimateBERT (Hugging Face Transformers)

- **Evaluation Metrics**:
  - Accuracy, Precision, Recall, F1-Score
  - Confusion matrices and classification reports

- **Topic Modeling**:
  - Sentence embeddings (MiniLM, ClimateBERT)
  - KMeans clustering for topic discovery
  - PCA visualization and keyword extraction

## 📁 Files

- `code/Climate_Sentiment_Classification_and_Topic_Discovery.ipynb`: Main Jupyter notebook with model implementations
- `results/Report.pdf`: Short report outlining results and evaluation

## 📦 Setup

Create a virtual environment and install dependencies:

```bash
pip install -r requirements.txt
```

## 📊 **Results**
	-	ClimateBERT significantly outperformed traditional models
	-	Embedding-based clustering identified distinct themes for climate risk and opportunity
	-	Demonstrated the importance of transfer learning and contextual understanding in text classification

⸻

This work was completed as part of an academic learning project.

👩‍💻 Author
	•	Amrita Moyade