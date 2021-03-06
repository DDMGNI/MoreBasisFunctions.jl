
# MoreBasisFunctions.jl

*Extends the BasisFunctions.jl package by additional basis functions (Lagrange, Bernstein, Splines).*


## Installation

MoreBasisFunctions.jl extends the [BasisFunctions.jl](https://github.com/JuliaApproximation/BasisFunctions.jl)
package from the [FrameFun.jl](https://github.com/JuliaApproximation/FrameFun.jl) ecosystem.
In order to conveniently install all dependencies, it is required to add the FrameFun registry.
From the Julia REPL, type `]` to enter Pkg mode and run
```julia
pkg> registry add https://github.com/FrameFunVC/FrameFunRegistry
```
Then, MoreBasisFunctions.jl can be installed by
```julia
pkg> add https://github.com/DDMGNI/MoreBasisFunctions.jl
```


## License

The MoreBasisFunctions.jl package is licensed under the [MIT "Expat" License](LICENSE.md).
