# 🎬 Netflix Movies and TV Shows Clustering (Unsupervised Learning)

This project uses **unsupervised machine learning** techniques to group Netflix titles based on their textual metadata (e.g. title, genre, description). The goal is to explore content-based clustering and recommendation strategies using NLP and clustering algorithms.

---

## 🎯 Objective

- Cluster Netflix Movies and TV Shows based on content similarity  
- Use text-based features for grouping (title, description, genre, etc.)  
- Visualize the clusters using dimensionality reduction techniques  
- Build a basic **content-based recommender system**

---

## 📂 Dataset


- **Size**: ~8800+ titles
- **Fields**: Title, Genre, Description, Cast, Country, Release Year, Duration, Type

---

## 🧠 Methodology

1. **Exploratory Data Analysis (EDA)**  
   - Missing value handling  
   - Type-wise and genre-wise distribution  

2. **Text Preprocessing & Feature Engineering**  
   - Combined fields: `title`, `description`, `type`, `genre`  
   - Text cleaning, lowercasing, stopword removal  
   - **TF-IDF Vectorization**

3. **Dimensionality Reduction**  
   - **PCA** (Principal Component Analysis) for visualization  

4. **Unsupervised Clustering**  
   - **KMeans Clustering**  
   - **Agglomerative Hierarchical Clustering**  
   - Silhouette Score & Dendrogram analysis

5. **Content-Based Recommendation**  
   - Cosine Similarity between TF-IDF vectors  
   - Recommend similar shows based on input show title

---

## 📈 Visualizations

- 📊 Genre distribution bar charts  
- 🧬 Dendrogram plots for hierarchical clusters  
- 📉 PCA 2D scatterplots to visualize clustering  
- 🔍 Similarity heatmaps  

---

## 🔧 Libraries Used

- `pandas`, `numpy`  
- `matplotlib`, `seaborn`, `plotly`  
- `sklearn` (TF-IDF, KMeans, AgglomerativeClustering, PCA, cosine_similarity)  
- `nltk` (stopwords)

---

## ✅ Key Results

- Optimal clusters found using KMeans and silhouette score  
- Clear separation between show types and themes using PCA  
- Functional content-based recommender built using TF-IDF + cosine similarity  

---

## 🧑‍💻 Author

**Madhusudan Mandal**  
📧 madhumandal49@gmail.com  
🔗 [GitHub Profile](https://github.com/Madhusudan3223)

---

## 📬 Try It Yourself

1. Clone the repo  
2. Run the notebook: `Unsupervied_Netflix_Movies_and_TV_Show_Clustering.ipynb`  
3. Input a Netflix title to get show recommendations!

---

## 🌟 Show Your Support

If you like this project, feel free to ⭐ the repo and share your feedback!

