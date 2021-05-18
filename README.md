## ViscousFlow.jl

_A framework for simulating viscous incompressible flows_

[![Stable](https://img.shields.io/badge/docs-stable-blue.svg)](https://JuliaIBPM.github.io/ViscousFlow.jl/stable) [![Dev](https://img.shields.io/badge/docs-dev-blue.svg)](https://JuliaIBPM.github.io/ViscousFlow.jl/dev)
[![Build Status](https://github.com/JuliaIBPM/ViscousFlow.jl/workflows/CI/badge.svg)](https://github.com/JuliaIBPM/ViscousFlow.jl/actions)
[![Coverage](https://codecov.io/gh/JuliaIBPM/ViscousFlow.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/JuliaIBPM/ViscousFlow.jl)
[![DOI](https://zenodo.org/badge/91933686.svg)](https://zenodo.org/badge/latestdoi/91933686)


## About the package

The purpose of this package is to enable easy setup and solution of viscous incompressible flows about bodies of various shapes. Documentation can be found at https://JuliaIBPM.github.io/ViscousFlow.jl/latest.

**ViscousFlow.jl** is registered in the general Julia registry. To install, type
e.g.,
```julia
] add ViscousFlow
```

Then, in any version, type
```julia
julia> using ViscousFlow
```
For examples, consult the documentation or see the example Jupyter notebooks in the Examples folder.

![](https://github.com/jdeldre/ViscousFlow.jl/raw/master/cylinderRe400.gif)

Many of the core aspects of the fluid-body interaction are based on the Method of Immersed Layers [1], which is an extension of the immersed boundary projection method [2].

[1]: Eldredge, J. D. (2021) "A method of immersed layers on Cartesian grids, with application to incompressible flows," [arXiv:2103.04521](https://arxiv.org/abs/2103.04521).

[2]: Taira, K. and Colonius, T. (2007) "The immersed boundary method: a projection approach," *J. Comput. Phys.*, 225, 2118--2137.
