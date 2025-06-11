**Topic Modeling with Latent Dirichlet Allocation (LDA) using Sklearn**

This project demonstrates how to perform topic modeling on a small corpus using Latent Dirichlet Allocation (LDA) implemented in scikit-learn. It includes end-to-end steps starting from text preprocessing to extracting interpretable topics from the documents.

**Key Features**

📂 Loading and combining multiple text documents as corpus.

🧹 Text preprocessing: tokenization, stopword removal, punctuation cleaning, and lemmatization.

📊 Feature extraction using TF-IDF and CountVectorizer.

🧠 Topic extraction using LDA (LatentDirichletAllocation) from sklearn.decomposition.

📌 Visualizing topics and their top contributing words.

🧾 Assigning the most probable topic to each document.

**Example Output**

Topics Identified:

Topic 1: ['movie', 'good', 'watch', 'book', 'weekend']

Topic 2: ['zealand', 'test', 'beating', 'world', 'championship']

Topic 3: ['weekend', 'want', 'watch', 'movie', 'book']
...
**Document-to-Topic Mapping**

Document 1 --> Topic 2

Document 2 --> Topic 1
...

**Technologies Used**

Python

Scikit-learn

NLTK

NumPy, Pandas

**Use Case**

Useful for beginners learning about:

Natural Language Processing (NLP)

Topic Modeling

Unsupervised machine learning

Document clustering and summarization
