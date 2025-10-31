### This repository contains code for the paper titled: 'Stochastic-Closure-Certificates'
### Link: ...
### Conference: ...
### Authors: Daniel Ajeleye, Vishnu Murali, and Majid Zamani
### Contact: daniel.ajeleye@colorado.edu
### Affiliation: University of Colorado Boulder

## Getting Started
##### 1. Download and install [Julia](https://julialang.org/). Installation instructions [here](https://docs.julialang.org/en/v1/manual/installation/).
##### 2. Install [Jupyter](https://jupyter.org/).
##### 3. Install the required Julia packages for the .ipynb files [how?](https://docs.julialang.org/en/v1/stdlib/Pkg/) to ensure all dependencies are available:
Open the Julia REPL and run:
using Pkg
Pkg.add([
    "JuMP",
    "MosekTools",
    "DynamicPolynomials",
    "MultivariatePolynomials",
    "LinearAlgebra",
    "Distributions" 
])

##### 3. Then to install TSSOS, do 
Pkg.add(url="https://github.com/wangjie212/TSSOS.jl")
##### 4. Now clone this repo or you download the files to your local machine
##### 5. Run jupyter notebook for each case study, the output are saved as .txt file on the same folder where the corresponding .ipynb are saved.
