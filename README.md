# Protein-desease-dashboard
## What is this repository for?
This repository has been designed to visualize the relationships in disease-gene associations. This work is based on data from articles obtained by the [Jense Lab](https://diseases.jensenlab.org/) project ([Github](https://github.com/larsjuhljensen/tagger)).

##  How to use?
### Prerequisites

You can install all requred Python libraries with:

```
pip install pandas numpy dash dash_bootstrap_components dash_cytoscape
```

### Data
Here are two files containing sample data for test runs.
File _gene-uniprot.txt_ contains **<gene name, uniprot_id, full name of protein, tissue>**.
File _human_disease_experiments_full.tsv_ contains data from [Experiments channel full](https://diseases.jensenlab.org/Downloads). 

### Running
Select the notepad you need and run the cells in sequence, then open the web page at [http://127.0.0.1:8050/](http://127.0.0.1:8050/).

### Example of proper work
![image](https://user-images.githubusercontent.com/108821649/180902607-59e20643-a642-470a-a62b-d7832e2ebdf7.png)
![image](https://user-images.githubusercontent.com/108821649/180902808-28393090-bd7a-4e2b-b130-ba2413d9e83b.png)
