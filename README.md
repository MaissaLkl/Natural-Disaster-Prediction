# 🌍 Natural Disaster Analysis and Prediction Project

## 📌 Overview
This project leverages machine learning models to analyze and predict natural disasters in Algeria based on historical data. It integrates classification, clustering, and visualization techniques to identify disaster patterns, their relationships with terrain types, and their impact metrics.

## 🚀 Features
✅ Data preprocessing and cleaning for disaster datasets  
✅ Decision tree-based disaster type prediction  
✅ Multiple clustering approaches (KMeans, DBSCAN, GMM, Agglomerative)  
✅ Impact analysis and visualization  
✅ Terrain-based pattern recognition  
✅ Comprehensive visualization suite  

## 📦 Requirements
```bash
pandas
numpy
scikit-learn
matplotlib
seaborn
```

## 📂 Project Structure
```
├── Data/
│   └── 1900_2021_DISASTERS.xlsx
├── Scripts/
│   └── script.py
└── README.md
```

## 🔧 Installation
1. **Clone the repository**:
```bash
git clone https://github.com/your-repo/natural-disaster-prediction.git
```
2. **Install required packages**:
```bash
pip install -r requirements.txt
```

## 📊 Usage

### 🧹 Data Preprocessing
Run the cell to clean and preprocess disaster data:
✔ Loads raw disaster data  
✔ Handles missing values  
✔ Converts data types  
✔ Adds terrain information  
✔ Exports cleaned dataset  

### 🔍 Classification Model
Execute the classification cell:
Features:
- Decision Tree Classifier
- Terrain-based disaster prediction
- Performance evaluation metrics
- Feature importance analysis

### 🔗 Clustering Analysis
Run the clustering cell:
Includes:
- Multiple clustering algorithms
- Optimal cluster determination
- Impact distribution analysis
- Terrain pattern visualization

## 🧠 Model Details

### 🎯 Classification Model
- **Algorithm**: Decision Tree
- **Hyperparameters**:
  - `max_depth`: 10
  - `min_samples_leaf`: 5
  - `min_samples_split`: 10
  - `class_weight`: 'balanced'

### 🔄 Clustering Models
- **Algorithms**:
  - KMeans
  - DBSCAN
  - Gaussian Mixture Model (GMM)
  - Agglomerative Clustering
- **Features**:
  - Automatic parameter tuning
  - Multiple validation metrics
  - Visualization tools

## ⚙ Data Processing
- Standard scaling
- Log transformation for skewed features
- One-hot encoding for categorical variables
- Missing value handling
- Outlier detection

## 📈 Visualizations
The project includes multiple visualization tools:
📌 Impact distribution plots  
📌 Terrain distribution heatmaps  
📌 Cluster characteristic analysis  
📌 Feature importance plots  
📌 Model performance metrics visualization  

## 📊 Results
Insights provided by the project:
✔ Disaster type prediction accuracy  
✔ Impact patterns across different terrains  
✔ Cluster characteristics and interpretations  
✔ Feature importance rankings  
✔ Model performance metrics  

## 🚧 Limitations & Future Work
🔹 Incorporate temporal features for better forecasting  
🔹 Implement more sophisticated imputation methods  
🔹 Add geospatial analysis for location-based predictions  
🔹 Enhance prediction lead time  
🔹 Include climate change indicators  

## 🤝 Contributing
1. **Fork the repository**
2. **Create your feature branch** (`git checkout -b feature-branch`)
3. **Commit your changes** (`git commit -m 'Add new feature'`)
4. **Push to the branch** (`git push origin feature-branch`)
5. **Submit a pull request** 🎉  

## 🙌 Acknowledgments
- **Data Source**: https://www.kaggle.com/datasets/brsdincer/all-natural-disasters-19002021-eosdis

💡 *"Predicting disasters today for a safer tomorrow in Algeria."* 🌱

