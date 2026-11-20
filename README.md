## 🧠 Pretrained Word2Vec Embeddings Exploration Using Gensim



## 📌 Project Overview

This project explores \*\*Word2Vec\*\* dense word embeddings using Google's pretrained \*\*`word2vec-google-news-300`\*\* model via the `gensim` library. It demonstrates how words are represented as 300-dimensional numerical vectors, how semantic similarity is measured, and how vector arithmetic captures semantic relationships and analogies\[cite: 3].



## 🎯 Project Objectives

\- Load and inspect the pretrained `word2vec-google-news-300` (300-dimensional) embeddings using `gensim.downloader`\[cite: 3].

\- Extract vector representations and dimensions for individual words (e.g., `king`, `cricket`)\[cite: 3].

\- Find top semantically similar words using `most\_similar()`\[cite: 3].

\- Compute similarity scores between word pairs using `similarity()` (e.g., `hockey` and `sports`)\[cite: 3].

\- Perform vector arithmetic (`king - man + woman`) to observe analogical reasoning in embedding space\[cite: 3].



## 🛠️ Technologies \& Libraries Used

\- Python\[cite: 3]

\- Gensim (`gensim.models`, `gensim.downloader`)\[cite: 3]

\- NumPy\[cite: 3]

\- Jupyter Notebook / Google Colab\[cite: 3]



## 📂 Model \& Embeddings Information

\- \*\*Pretrained Model:\*\* `word2vec-google-news-300` (\~1,662.8 MB download via `gensim.downloader`)\[cite: 3]

\- \*\*Vector Dimensionality:\*\* 300 dimensions per word vector\[cite: 3]



## 🔍 Key Experiments \& Observations

1\. \*\*Word Vector Extraction:\*\* Retrieved 300-dimensional dense vectors (`shape = (300,)`) for words like `king` and `cricket`\[cite: 3].

2\. \*\*Most Similar Words (`most\_similar`):\*\*

&#x20;  - For `'cricket'`, top matches include `cricketing` (\~0.837), `cricketers` (\~0.817), and `Test\_cricket` (\~0.809)\[cite: 3].

&#x20;  - For `'happy'`, top matches include `glad` (\~0.741), `pleased` (\~0.663), and `ecstatic` (\~0.663)\[cite: 3].

3\. \*\*Pairwise Word Similarity (`similarity`):\*\* Calculated semantic similarity between `'hockey'` and `'sports'` (\~0.535)\[cite: 3].

4\. \*\*Vector Arithmetic / Analogy (`king - man + woman`):\*\* Computed a resulting 300D vector whose nearest neighbors include `king`, `queen` (\~0.730), `monarch` (\~0.645), and `princess` (\~0.616)\[cite: 3].



## ⚙️ How to Run This Project

1\. Install Python and Jupyter Notebook (or use Google Colab)\[cite: 3].

2\. Install `gensim`:

&#x20;  ```bash

&#x20;  pip install gensim

&#x20;  ```\[cite: 3]

3\. Open `Word2Vec\_Embeddings\_Exploration.ipynb` and run all cells sequentially (note that downloading `word2vec-google-news-300` requires internet access and \~1.7 GB space)\[cite: 3].



## 📁 Project Structure

```text

Word2Vec-Embeddings-Exploration/

│

├── Word2Vec\_Embeddings\_Exploration.ipynb

└── README.md

```\[cite: 3]



## 👩‍💻 Author

Sakshi Kachare 

Email: sakshikachare444@gmail.com 

GitHub: https://github.com/Sakshi-Kachare

⭐ This project demonstrates practical exploration of pretrained Word2Vec embeddings, semantic similarity, and vector arithmetic in Natural Language Processing.

