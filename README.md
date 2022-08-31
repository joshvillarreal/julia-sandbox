# julia-sandbox
Playground to explore Julia. Some resources that I found helpful:
- https://ucidatascienceinitiative.github.io/IntroToJulia/

## Installation
To install Julia on my local machine for use in Jupyter notebooks, I followed these steps:
1. <a href="https://julialang.org/downloads/">Download</a> the latest version of Julia directly from the developers.
2. Launch the Julia app and key in the following commands, which take a minute or so to run:
  ```
  julia> using Pkg
  julia> Pkg.add("IJulia")
  ```
3. You should now be able to launch Jupyter, and can create a notebook using Julia.
