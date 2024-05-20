# Setting up development environment

1. Install Anaconda.
1. Create working project i.e. `data-analytics` in this case.
1. In the project, enable virtual environment for conda.
    1. If starting the project then `conda create -n <virtual environment name> python=3.11.7 anaconda`
        1. Ensure you create environment.yml config to enable other developerss to use same environment. `conda env export > environment.yml`
    1. If using an existing project with environment.yml then `conda env create -f environment.yml`
1. Install git
1. Initiate the git repository `git init`
1. Create a `.gitignore` file
1. Install pre-commit `pip install pre-commit`
1. `conda activate <virtual environment name>`

20/05 - module 0