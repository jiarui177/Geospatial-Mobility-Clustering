# Saciva: Geospatial Student Mobility Clustering

## 📌 Project Overview
International students face significant challenges in identifying suitable relocation areas due to the lack of integrated data on housing, safety, and climate. 

This project, developed during the **Fall 2024 AI Studio**, applies **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** to 6,800+ geospatial data points. By uncovering hidden mobility patterns beyond administrative city boundaries, we provide preference-based location intelligence to support student decision-making.

## 🚀 Key Achievements
* **Advanced Clustering:** Identified **294 distinct clusters** from unstructured geospatial data with a **silhouette score of 0.868**.
* **Feature Integration:** Constructed comprehensive cluster profiles by merging housing affordability, safety metrics, climate data, and network accessibility.
* **Business Impact:** Developed a recommendation framework that aligns student preferences (e.g., "safe and affordable") with specific geospatial clusters.

## 🛠️ Tech Stack
* **Language:** Python
* [cite_start]**ML Algorithms:** DBSCAN (Unsupervised Learning) [cite: 120]
* **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
* **Tools:** Jupyter Notebook

## 📂 Project Structure & Files
* `University Clusters.ipynb`: Implementation of the DBSCAN algorithm, including epsilon ($\epsilon$) tuning and noise reduction.
* `profiling_all.ipynb`: Detailed cluster profiling and demographic/environmental analysis.
* `data/`:
    * `final_merged_data_with_weather.csv`: Integrated dataset containing climate and environmental features.
    * `latitude_longitude_with_clusters.csv`: The final output dataset mapping each location to its identified cluster.
* `Saciva_Final_Project_Presentation.pptx`: Full project walkthrough, visualization of results, and strategic recommendations.

## 📊 Methodology Highlights
1. **Data Pre-processing:** Cleaned and standardized 6,800+ geospatial points across various regional boundaries.
2. [cite_start]**DBSCAN Modeling:** Chose DBSCAN over K-Means to effectively handle clusters of arbitrary shapes and identify outliers (noise) in sparse areas[cite: 120].
3. **Cluster Profiling:** Defined "Student-Centric" zones by evaluating the trade-off between cost of living and amenity accessibility within each cluster.

## 💡 Potential Public Sector Application
This framework can be adapted for **Urban Planning** and **Public Transportation Optimization** by identifying high-density mobility hubs that require enhanced infrastructure support.
