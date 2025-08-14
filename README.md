# LinkedIn Job Posts Analysis & Clustering

## 📌 Project Overview
This project analyzes a large dataset of **LinkedIn Job Posts** to uncover insights about the job market and cluster similar job postings based on their attributes.  
The workflow covers **data cleaning, preprocessing, balancing, modeling, dimensionality reduction, and visualization**.

---

## 🎯 Objectives
- Clean and prepare job post data from LinkedIn.
- Handle missing values and inconsistent formatting.
- Balance unbalanced data for better modeling.
- Apply multiple **unsupervised learning algorithms** for clustering.
- Use **PCA** to reduce dimensionality and visualize clusters.
- Extract insights about the job market trends.

---

## 📂 Dataset
- **Source**: LinkedIn job posts dataset.
- **Size**: ~21,475 rows × 13 columns (after cleaning).
- **Key Features**:
  - `job_title`
  - `job_function`
  - `employment_type`
  - `company_size`
  - `industry`
  - `location`
  - and more…

---

## 🛠 Methodology

### 1. Data Cleaning
- Solved real scraped data using NLP.
- Removed duplicates and missing values.
- Standardized text formatting (lowercasing, trimming spaces).
- Normalized categories (e.g., employment type, job functions).
- Converted non-English characters when necessary.

### 2. Data Preparation
- Encoding categorical variables.
- Normalization of numerical features.
- Handled unbalanced data using **oversampling** to reduce computational cost.

### 3. Modeling
Applied different clustering algorithms:
- **KMeans** – partitions data into k clusters by minimizing variance.
- **Agglomerative Clustering** – hierarchical bottom-up clustering.
- **DBSCAN** – density-based clustering for arbitrary shapes.
- **MeanShift** – detects clusters based on density peaks.
- **Gaussian Mixture Models** – probabilistic clustering assuming Gaussian distributions.

### 4. Dimensionality Reduction
- **PCA (Principal Component Analysis)** used to:
  - Reduce feature dimensions.
  - Improve visualization of clusters.
  - Speed up computation.
    
### 5. Randome Search
 - Random search for hyper-parameter optimization
 - Increase the scores

### 6. Visualization
- **Heatmaps** after normalization to understand feature correlations.
- **Cluster plots** for different algorithms.
- Distribution plots for job types, industries, and company sizes.

---

## 📊 Results & Insights
- Discovered main job clusters across industries.
- Identified the most common job functions and employment types.
- Found patterns in locations and company sizes.

---

## 📑 Presentation
You can view the full project presentation here:  
[📄 View Presentation (PDF)](./LinkedIn_Posts_insights_Presentation.pdf)

---
## 📌 Dependencies
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn
- plotly-express

## 👥 Authors

**Abdelmoneim Adel**  
📧 **Email** `abdelmoneim.adel5@gmail.com`  
🌐 [LinkedIn Profile](https://www.linkedin.com/in/abdelmoneim-adel)  

**Abdallah Mahmoud**  
📧 **Email** `abdallahsoussa123@gmail.com`  
🌐 [LinkedIn Profile](https://www.linkedin.com/in/abdallah-mahmoud-6a9058308)  

**Mohamed Hatem**  
📧 **Email** `mohamedhatemwaheed@gmail.com`  
🌐 [LinkedIn Profile](https://www.linkedin.com/in/mohamed-hatem-921936258)  

**Rawan Mostafa**  
📧 **Email** `rgfreelancing7@gmail.com`  
🌐 [LinkedIn Profile](https://www.linkedin.com/in/rawan-elkhemy-0a3bab279)  


---

## 📦 Installation
```bash
# Clone the repository
git clone https://github.com/AbdelmenamAdel/LinkedIn-Job-Posts-Insights-NTI.git

# Navigate to project folder
cd LinkedIn-Job-Posts-Insights-NTI
```
ذذ  
## 🚨 Contributing

- Contributions are welcome 💜
- If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.








