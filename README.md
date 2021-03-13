# Julia project : Compare the Julia programming language to Python and R in structural bioinformatics.

#### Author : Audrey Fortune
#### Cursus : M2 Bioinformatique
-----------------

## Description 
The aim of this project is to carry out the analysis of protein structures (sequence alignment, contact card, etc.). <br/>
***Initiation to Julia*** : Here, we are going to compare the following programming languages : Python, R, Julia. 

## Analysis
The programs implemented allow the following analysis to be performed :  <br/>
* Reading a PDB file.
* Visualisation of 3D structures.
* Sequence alignment.
* Contact map

## Application example
- "1RGB.pdb" : Phospholipase A2 from *Vipera ammodytes meridionalis*.
- "6HQ1.pdb" : Globular domain from human histone H1.0.
- "1UHM.pdb" : Globular domain of linker histone homolog Hho1p from *S. cerevisiae*.

## Required
- [Python 3.8](https://www.python.org/downloads/)
- [Julia 1.5](https://julialang.org/downloads/)
- [R 4.0](https://cran.r-project.org/)
- Jupyter / Jupyterlab notebook ([Anaconda](https://www.anaconda.com/products/individual#Downloads) / [Miniconda](https://docs.conda.io/en/latest/miniconda.html)) 

## Packages
### 1. Julia  <br/>
BioStructures, BioAlignments, MIToS, PDBTools, Bio3DView, RCall
### 2. Python  <br/>
Biopython, Py3Dmol
### 3. R  <br/>
Bio3D, Biostring

## How to use the script 'projet_long_Julia.ipynb' <br/>
 ```
julia> using Pkg
julia> Pkg.add("IJulia")
julia> using IJulia
julia> notebook()
```

## How to use the script 'projet_long_Python.ipynb' <br/>
With conda : ```  conda install -c conda-forge notebook ```  <br/>
With pip : ``` pip install notebook ``` <br/>
 ``` $ jupyter notebook``` <br/>


## How to use the script 'projet_long_R.ipynb' <br/>
Requires a anaconda environment. <br/>


## Citation

Greener JG, Selvaraj J and Ward BJ. BioStructures.jl: read, write and manipulate macromolecular structures in Julia, Bioinformatics (2020) - [link](https://academic.oup.com/bioinformatics/article/36/14/4206/5837108?guestAccessKey=aec90643-1d43-4521-9883-4a4a669187da)
