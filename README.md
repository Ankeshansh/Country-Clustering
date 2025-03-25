# Country-Clustering

This project applies machine learning techniques to cluster countries based on various economic, social, and demographic indicators. Using **Principal Component Analysis (PCA)** for dimensionality reduction and **KMeans & Agglomerative Clustering**, the project provides insights into country similarities.  


## **About Dataset**

Clustering the Countries by using Unsupervised Learning for HELP International Objective: To categorise the countries using socio-economic and health factors that determine the overall development of the country.

## **Features**  
- **Dimensionality Reduction:** PCA is used to extract the most relevant features.  
- **Clustering Algorithms:** Implementation of KMeans and Agglomerative clustering.  
- **Visualization:** Cluster results are plotted for better interpretation.  
- **Performance Evaluation:** Silhouette score used for assessing clustering quality.  

## **Directory Structure**  
```
root/                           
├── Country_Clustering.ipynb    # Jupyter Notebook containing data analysis, clustering, and visualizations  
├── data/                       # Folder storing the dataset used for clustering  
├── results/                    # Folder where output visualizations (graphs, charts) are saved  
└── README.md                   # Documentation file explaining the project  
```

## **Results**  

| Clustering Method  | Silhouette Score |
|--------------------|-----------------|
| KMeans            | 0.38            |
| Agglomerative     | 0.35            |


## **Installation & Usage**  
Clone the repository and install dependencies:  
```bash
git clone https://github.com/your-repo/country-clustering.git
cd country-clustering
pip install -r requirements.txt


