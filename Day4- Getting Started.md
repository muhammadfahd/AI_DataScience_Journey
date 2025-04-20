# Day 4  

## Getting Started Guide  - Before You Begin

> To ensure a smooth and efficient experience, download the necessary tools on your local PC. This will help you manage your projects more effectively.

1. [Download the Latest Version of Python ]('https://www.python.org/downloads/') <br>
2. [Install a Code Editor or IDE ]('https://code.visualstudio.com/') <br>
2. **Boost your productivity by installing extensions** that streamline your workflow. Some popular options include :
   1. Python 
   2. vscode-icons
   3. Jupyter
   4. Suitable Theme like Jellyfish
   5. GitHub Copilot 
   6. Prettier -Code Formatter
   7. Markdown All in one
3. [Install MiniConda](#installing-miniconda)
4. **Install important libraries** using pip: <br>
   1. Pandas
   2. Numpy
   3. Matplotlib
   4. plotly
   5. seaborn
**Example** 
  ` pip install pandas numpy matplotlib plotly seaborn `


---
### Installing MiniConda
Miniconda is a lightweight, minimal installer for conda, a package manager for data science and scientific computing. 
It's a stripped-down version of Anaconda, a popular distribution for data science and machine learning.

#### Why is Miniconda important?
Miniconda is important because it allows you to:

1. **Manage packages**: Easily install, update, and manage packages 
2. **Create environments**: Create isolated environments for different projects, ensuring reproducibility and avoiding package conflicts.
3. **Save space**: Miniconda is a smaller download compared to Anaconda, making it ideal 

#### Basic Miniconda Commands

Here are some basic commands to get you started with Miniconda:
1. **Create a new environment** - Create a new environment with the specified name.
`conda create --name myenv
`

1. **Activate an environment** - it will activate the specified environment.
 ` conda activate myenv `


3. **Deactivate an environment** -  Deactivate the current environment.
` conda deactivate `

4. **Install packages** -  Install the specified package in the current environment.
` conda install package_name `


1. **List packages** - List all packages installed in the current environment.
    ` conda list `

2. **Update packages** - Update all packages in the current environment
` conda update --all `

1. **Remove a package** -  Remove the specified package from the current environment
` conda remove package_name `
8. **Remove an environment** - Remove the specified environment.
`conda env remove --name myenv `

For more information, you can refer to the [Conda Cheat Sheat]('https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf')