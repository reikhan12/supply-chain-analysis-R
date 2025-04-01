# supply-chain-analysis-R
Supply chain performance analysis with advanced visualizations and machine learning using R (DataCoSupplyChainDataset)



## 📌 Project Highlights

- 📊 Time series analysis of shipping performance
- 🗺️ Geospatial maps of delivery risks by state
- 🧩 Market & customer segmentation
- 🔄 Animated model improvement over iterations
- 📈 Boxplots, lollipop charts, Sankey diagrams
- 🌲 Random Forest classifier to predict late delivery risk
- 🧠 Feature importance analysis

---

## 📁 Files in This Repository

Supply Chain Analysis/ │ ├── R_Projetcs.R # Main R script ├── model_improvement.gif # Animated GIF (model improvement) └── [Dataset to be added manually] # DataCoSupplyChainDataset.csv (required to run)


---

## 📚 Dataset Information

**Dataset Used**: [DataCoSupplyChainDataset.csv](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)  
(⚠️ Please download and place the dataset in the working directory as it's not included due to size restrictions.)

---

## 📦 Required R Packages

Install the required packages:

```r
install.packages(c("dplyr", "ggplot2", "lubridate", "caret", "randomForest", 
                   "sf", "maps", "rnaturalearth", "networkD3", "gganimate", 
                   "gifski", "av", "ggrepel", "gridExtra", "tidyr", 
                   "reshape2", "treemap", "plotly"))
🚀 Key Visualizations

Yearly late delivery trend (line plot)
State-level risk map (ggplot2 + maps)
Sankey diagram of high-risk flows (networkD3)
Rolling average shipping performance
Feature importance chart
Correlation heatmap
Boxplot for shipping delays
🧠 Machine Learning Model

Algorithm: Random Forest
Task: Classification of late delivery risk
Evaluation: R-squared, RMSE, residual plots
🤝 Contributions

Feel free to fork, explore, or suggest improvements!

📬 If you find this project helpful, please give it a ⭐ star!
