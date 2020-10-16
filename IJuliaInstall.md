# Install `IJulia` in win or linux systems
If you encountered error will `add IJulia`, please try the following instructions in order:

```julia
] # change to Pkg mode
registry add General
# It will take a few minutes to clone the General.jl repo.
add IJulia
build IJulia
using IJulia
notebook()
```
Julia will ask for permission to install `conda`, it will take a few minutes. The `IJulia` will probably be well installed.

