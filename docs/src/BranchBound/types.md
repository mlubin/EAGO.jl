## BnBModel
The `BnBModel` structure contains all information used over the course of the
Branch and Bound.

```@docs
BnBModel
```

As a default, the model constructor initializes with `Vector{Interval{Float64}}`
storage type.

```@docs
BnBModel(X::Vector{Interval{Float64}})
```

## BnBSolver
The `BnBSolver` options regarding how to solve the problem and routines used in
it's solution.

```@docs
BnBSolver
```

The default initialization for `BnBSolver` is given below:

```@docs
BnBSolver()
```