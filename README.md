# cb2330-PRO1-Pair23

# What the project is...

Course project for CB2330 (KTH), pair 23.

In this project we replicate the paper's fitting method with one and two Poisson models on novel mutation counts obtained from mutator type yeast cells. We have performed forwards simulation with the reported parameters and backwards estimation of the parameters along with calculation of parameter uncertaintly. 

Kennedy, S. R., Schultz, E. M., Chappell, T. M., Kohrn, B., Knowels, G. M., & Herr, A. J. (2015). Volatility of Mutator Phenotypes at Single Cell Resolution. PLOS Genetics, 11(4), e1005151. https://doi.org/10.1371/journal.pgen.1005151

## What we found...

- Data: 233 novel mutations across 85 cell divisions from 8 lineages of yeast mutator type cells.

Summary statistics show that mean is 2.74 and variance is 5.72, indicating that the data is overdispersed. No mutations observed in 20 divisions.

We have performed forwards simulation, backwards estimate of parameters and calculated parameter uncertainty for both the models and compared them using AIC.

## How to run...

The project can be run as a Jupyter Notebook using a Python kernal with the following packages:

numpy
matplotlib
openpyxl
jupyter
pandas

## Contents...

- `project.ipynb`: The project notebook

- `data/mutation_counts.xlsx`: mutation counts per cell division extracted from `S2_Dataset.xlsx`

- `data/S1_Dataset.xlsx`, `S2_Dataset.xlsx`, `S3_Dataset.xlsx`: the paper's supplementary data.

- `data/README.md`: where the numbers come from and their shape.