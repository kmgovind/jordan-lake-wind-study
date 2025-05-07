# jordan-lake-wind-study
Characterizing historical wind data at Jordan Lake, NC

# Software setup
## Setting up the julia environment
1. Install Julia from the [official website](https://julialang.org/downloads/).
2. Add the required packages by running the following in the Julia REPL:
    ```julia
    using Pkg
    Pkg.activate(".")
    Pkg.instantiate()
    ```
3. Verify the environment is set up by running any provided Julia scripts or notebooks.

## Setting up the python environment
1. Create a virtual environment: `python -m venv venv`
2. Activate it: `venv\Scripts\activate`
3. Install dependencies: `pip install -r requirements.txt`