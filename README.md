# Analysis of the Erdős Collaboration Network

## Project Overview
This project performs a comprehensive structural analysis of the Erdős collaboration graph, a network representation of mathematical co-authorships compiled from the publication record of Paul Erdős. Using Python and graph-mining techniques, this analysis identifies influential researchers, extracts community structures, and highlights stable collaborative clusters.

## Tools & Technologies
* **Language:** Python
* **Network Analysis:** NetworkX
* **Machine Learning & Math:** Scikit-learn (KMeans), SciPy (Spectral Clustering)
* **Data Visualization:** Matplotlib (with a focus on clear, data-driven storytelling)

## Key Findings
* **Network Structure:** The graph contains 6,927 nodes and 11,850 edges, forming a sparse network with a massive dominant connected component.
* **Centrality Analysis:** Computed Degree, Closeness, and Betweenness centralities. Paul Erdős emerged as the primary hub, carrying 70% higher degree centrality than the second-ranked author and a 0.81 betweenness score.
* **Community Detection:** Evaluated the network using **Girvan-Newman** and **Spectral Clustering** algorithms. Girvan-Newman revealed distinct subcommunities within Erdős's network (Modularity Q=0.40).
* **Heavy Hitters & Cliques:** Identified 5 cliques of size 8 that form a dense, stable core of mutually collaborating mathematicians.

## Repository Contents
* `Erdos_analysis_Diell_Davide.ipynb`: Jupyter Notebook containing all data preprocessing, exploratory data analysis (EDA), and algorithm implementations.
* `Erdos_report.pdf`: A concise 5-page report detailing the hypotheses, methodological choices, visualizations, and conclusions. 

## How to Run
1. Clone the repository.
2. Ensure you have the required libraries installed: `pip install networkx numpy matplotlib scipy scikit-learn`
3. Open the Jupyter Notebook and execute the cells.
