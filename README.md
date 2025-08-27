# 🌸 PCA + Hierarchical Clustering on Iris Dataset  

## 📌 Project Overview  
This project demonstrates **Dimensionality Reduction using PCA** followed by **Hierarchical Clustering** on the famous **Iris dataset**.  

The Iris dataset originally contains 3 classes (**Setosa, Versicolor, Virginica**). However, in this project we drop the labels to simulate an **unsupervised learning scenario**.  

---

## 🧠 Steps Performed  
1. **Data Preprocessing**  
   - Removed the `species` column.  
   - Standardized the data using `StandardScaler`.  

2. **Principal Component Analysis (PCA)**  
   - Reduced dataset from **4D → 2D**.  
   - Extracted the **top 2 Principal Components (PC1 & PC2)**.  
   - Visualized data in 2D.  

3. **Hierarchical Clustering (Agglomerative)**  
   - Created a dendrogram to choose the number of clusters.  
   - Selected **2 clusters** (largest vertical cut in dendrogram).  
   - Trained `AgglomerativeClustering` model with **Ward linkage**.  
   - Visualized clustered points on PCA-transformed space.  

---

## 📊 Results & Insights  
- **PCA Visualization** → Data compressed into 2 principal components.  
- **Clustering Output** → 2 clusters were identified.  
- **Reason for 2 clusters** → While Iris dataset has 3 species, unsupervised clustering found overlap between **Versicolor & Virginica**, grouping them together.  

📌 This shows how **PCA + Clustering** can simplify data but does not always reproduce exact labels.  

---

## 🚀 Key Learnings  
- PCA reduces dimensionality while preserving maximum variance.  
- **Eigenvalues** = variance explained.  
- **Eigenvectors** = directions of variance (Principal Components).  
- Hierarchical clustering builds **tree-like structures (dendrograms)** for flexible cluster selection.  
- Unsupervised clustering is about **similarity patterns**, not predefined labels.  

---

## 📂 Files in Repository  
- `pca_clustering.py` → Code for PCA + Agglomerative clustering.  
- `README.md` → Project documentation.  
- Sample plots (PCA visualization + dendrogram + clusters).  

---

## 👨‍💻 Author  
**Saifullah Umar**  
- 🎓 BS Artificial Intelligence Studentat Nutech University Islamabad, pakistan
- 💻 Aspiring ML Engineer  
- 🌐 [GitHub Profile](https://github.com/SaifUllahUmar0317/)
