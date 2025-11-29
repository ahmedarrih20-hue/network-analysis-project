# network-analysis-project
A network analysis and clustering project based on the BPI Challenge 2012 dataset. 
# network-analysis-project

A network analysis and clustering project based on the BPI Challenge 2012 dataset.  
This project explores how to extract insights from event logs using clustering, graph analysis, and dimensionality reduction.

---

## 📂 Project Structure
network-analysis-project/
├── README.md # This file
├── Untitled1.ipynb # Main Jupyter Notebook with all analysis
├── results_report.pdf # Final report with results & conclusions
├── node_data.csv # Cleaned dataset used in t-SNE (optional)
├── references.txt # Sources used (optional)

## 📊 Dataset

- **Source**: BPI Challenge 2012 (TU/e Process Mining group)
- **Content**: Event logs from a Dutch financial institution
- **Link**: [[https://data.4tu.nl/articles/dataset/BPI_Challenge_2012/12689204](https://data.4tu.nl/articles/dataset/BPI_Challenge_2012/12689204)]

---

## 🛠️ How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/ahmedarrih20-hue/network-analysis-project.git
   cd network-analysis-project
Open network-analysis-project.ipynb using Jupyter Notebook or VS Code

Run the notebook step by step. It includes:

Data preprocessing

Graph metrics extraction

KMeans clustering

t-SNE visualization

🧪 Tools Used

Python (pandas, networkx, sklearn, matplotlib)

Orange (for visual t-SNE exploration)

Jupyter Notebook

✅ Results

We tested 3 different dimensionality reduction methods:

PCA (Principal Component Analysis)

Force-Directed layout from NetworkX

t-SNE with clustering visualized in Orange & Python

👉 t-SNE gave the clearest visual separation between communities.

📚 References

1. BPI Challenge 2012 Dataset- https://data.4tu.nl/articles/dataset/BPI_Challenge_2012/12689204/1
2. pm4py Documentation — https://github.com/eon-collective/pm4py-core 
3. Orange Data Mining — https://orangedatamining.com/  
4. NetworkX Library — https://networkx.org/
5.  Wikipedia - Community structure: - https://en.wikipedia.org/wiki/Community_structure
