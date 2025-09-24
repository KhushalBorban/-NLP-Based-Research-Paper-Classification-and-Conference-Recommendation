# -NLP-Based-Research-Paper-Classification-and-Conference-Recommendation
NLP-Based Research Paper Classification and Conference Recommendation

This project was developed during the KDSH Hackathon (Jan’24 – Feb’24). It builds an NLP-powered system to classify research papers as publishable and recommend the top 5 most suitable conferences for submission, based on paper content and alignment. https://drive.google.com/drive/folders/1HGsyStlIUdLOU4vnkzUqfSxVZDTLYcsh?usp=sharing

📌 Features

Conference Recommendation System: Suggests 5 most relevant conferences for each research paper.
Publishability Classification: Distinguishes between publishable vs. non-publishable research papers.
NLP Pipeline: Implemented end-to-end text preprocessing and feature extraction.
Hybrid Modeling: Leveraged TF-IDF features, transformer embeddings, and ensemble models for robust classification.
Evaluation Dataset: Trained on 25 labeled research papers and tested on 125 unseen papers.

🛠️ Methods & Workflow

1. Data Preparation
Collected and labeled research papers with conference assignments.
Preprocessed text (tokenization, stopword removal, lemmatization).

2. Feature Engineering
TF-IDF vectors for classical ML models.
Transformer embeddings (BERT/related encoders) for semantic understanding.
Combined into ensemble representations.

3. Modeling
Binary Classification: Publishable vs. non-publishable papers.
Conference Recommendation: Ranked similarity scores to recommend top-5 conferences.

4. Evaluation
Training set: 25 research papers.
Test set: 125 papers.
Metrics: Accuracy, Precision-Recall, and Recommendation Validity.

📊 Results

Publishability Classification: Successfully separated publishable vs. non-publishable works.
Conference Recommendation: Top-5 conference suggestions aligned well with ground-truth labeled data.
Demonstrated feasibility with limited dataset (25 train + 125 test).

🎯 Applications

Automated conference recommendation for researchers.
Assisting review committees in paper triage.
Supporting academic publishing workflows.

📖 References

TF-IDF Explained
BERT: Pre-training of Deep Bidirectional Transformers (Devlin et al., 2019)
Conference Ranking Benchmarks
