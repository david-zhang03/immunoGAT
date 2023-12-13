# immunoGAT

immunoGAT is a graph attention transformer model designed to process both structural and sequence information of peptide-MHC complexes for immunogenicity prediction.  

## Setup:

### Clone immunoGAT git repo:
```bash
git clone https://github.com/david-zhang03/immunoGAT.git
```

### Environment setup: 

If you do not have Anaconda installed, follow these [instructions](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)

To verify installation,  
```bash 
conda list
```

To install environment, 
```bash
conda env create -f environment.yml
```

To activate,  
```bash
conda activate immunoGAT
```

### Usage: 

Due to file sizes, first generate graphs following instructions in `expand_ablation_graph.ipynb`. This allows you to generate graphs from the PDB files found in `SingleAllele` and `Multiallele`.

To reproduce the results from the baseline GAT model, follow the instructions in `baselineGAT.ipynb`. 

To reporduce the results from immunoGAT, follow the instructions in `immunoGAT.ipynb`.
