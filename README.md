# RNA Structure Analysis using PDBe Search API

This project uses the PDBe Search API to retrieve, process, and visualize RNA structural data from the Protein Data Bank in Europe (PDBe). It categorizes RNA molecule types such as rRNA, tRNA, mRNA, and others using metadata fields and visualizes their counts.

##  Features

- Query PDBe entries using `solrq` with multiple search parameters
- Group and filter results using fields like `molecule_type`, `GO mapping`, `organism`, etc.
- Convert results into tidy Pandas DataFrames
- Count and visualize RNA molecule types using bar plots

##  Dependencies

- Python 3.x
- pandas
- numpy
- requests
- matplotlib
- seaborn
- solrq

##  Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/RNA_stats_PDB.git
   cd RNA_stats_PDB