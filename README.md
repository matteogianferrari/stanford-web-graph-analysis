# Stanford Web Graph Analysis

The Stanford Web Graph represents the website structure of Stanford University, providing a detailed snapshot of how web pages within the Stanford domain are interconnected. The dataset, which can be downloaded from https://networkrepository.com/web-Stanford.php, consists of node IDs representing individual web pages and edges representing hyperlinks between these pages.

This notebook contains the necessary code to process the raw data, transforming it into a format suitable for import into Neo4j. Following the data processing steps, we perform exploratory data analysis (EDA) on the graph to uncover different informations.

After the initial exploration, we delve deeper into two specific questions:
1. Community Analysis: Identifying and analyzing inter-community connections within the graph.
2. Home Page Detection: Identifying the node with the highest probability of being the homepage of the Stanford website. This involves using a combination of graph algorithms.

Through this analysis, we aim to gain a comprehensive understanding of the structural properties of the Stanford Web Graph and answer these targeted questions with deeper insights.

The development environment is set up with VSCode, utilizing the Jupyter and Python extensions to connect locally with the Neo4j Desktop App.

## Folder Structure

- **notebooks**: Contains the Python notebook for the graph analysis.
- **img**: Contains images used within the notebook.
- **data**: Contains the raw input data and the .csv files to be imported into Neo4j.
- **config**: Contains the configuration file for the Neo4j DBMS.

## Setup Instructions

To run the notebook, follow these steps:

1. **Install Required Extensions:**
    - Jupyter Extension Pack (`ms-toolsai.jupyter`)
    - Python Extension (`ms-python.python`)
    
2. **Run the Notebook:**
    1. Execute the first block of code in the notebook.
    2. When prompted to select a kernel, click "Select another kernel".
    3. Choose "Python Environments" as the kernel type.
    4. Select "Create Python Environment".
    5. Choose "Venv" as the environment type.
    6. Pick your preferred Python installation.
    7. If prompted by VSCode, install `ipykernel`.
    
3. **Follow the Notebook Instructions:**
    - Proceed with the notebook from the beginning, following the instructions and executing code blocks as directed.

Ensure you have all dependencies installed and configured properly to successfully analyze the Stanford web graph data.
