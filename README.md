# network-science-graph-learning-final-project
NET 4103/7431 Network Science and Graph Learning – Final Project.  Professor: Vincent Gauthier.  Submitted by : Arjun Saseendran
# Network Science and Graph Learning - Final Project

**Student:** Arjun Saseendran  
**Course:** NET 4103/7431  
**Professor:** Vincent Gauthier  
**Institution:** Telecom SudParis

## Project Overview
This project analyzes the Facebook100 dataset, implementing social network analysis, assortativity analysis, link prediction, label propagation, and community detection algorithms.

## Repository Structure
- `data/` - Facebook100 network files (.gml format)
- `results/` - Generated plots, CSV files, and outputs

## Implemented Questions

### Question 2: Social Network Analysis
- Degree distribution analysis
- Clustering coefficient computation
- Network density analysis

### Question 3: Assortativity Analysis
- Analysis across 100 networks
- 5 attributes: Student/Faculty, Major, Degree, Dorm, Gender

### Question 4: Link Prediction
- **Custom implementation** (no NetworkX built-ins used)
- Algorithms: Common Neighbors, Jaccard, Adamic/Adar
- Tested on 10 networks
- Evaluation: Precision@k, Recall@k

### Question 5: Label Propagation
- Semi-supervised node classification
- Attributes: Dorm, Gender
- Network: Duke14

### Question 6: Community Detection
- Research question: Gender segregation in communities
- Algorithm: Louvain method
- Networks: Caltech, Reed, Haverford, Duke

## How to Run

### Prerequisites
```bash
pip install networkx numpy pandas matplotlib scipy
```

```

## Key Files
- `Final.ipynb` - Complete analysis notebook

## Results
All results, plots, and analysis are available in the `results/` directory and in the final report (PDF).

## Note on Implementation
All link prediction algorithms (Common Neighbors, Jaccard, Adamic/Adar) were implemented from scratch without using NetworkX's built-in functions, as required by the assignment.
```

---
