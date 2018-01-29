# sci_python_seminar

## Virtualenv instalation (recommended for advanced linux users)

* isolated python repository
* no need for admin access to install packages

Instalation:
    install python (the best way depends on your OS - ask tutor for details) / or use system python if available
    python get_pip.py
    pip install virtualenv

Create new env:

    mkdir new_env
    virtualenv --python=PATH_TO_PYTHON_GOES_HERE new_env
    
Activate the env:

    source new_env/bin/activate
    
### Jupyter

It is a framework that allows manipulations (creation, editing and running) on notebooks.
Notebook is a document, which contains both code and rich text elements (paragraph, equations, figures, links, etc...)

Instalation:
   
    pip install jupyter
    
Running:
    
    jupyter notebook
    
## Anaconda instalation (the best option for Windows and recommended for general linux users)

* python distribution with many scientific packages included
* has its own package manager
* the easiest way to work with python
* virtualenv is already included
* the best decision for python on Windows

Instalation: https://www.anaconda.com/download

Create new env:

    conda create -n new_env python=3.6
    
Activate the env:
* Windows: activate new_env
* macOS and Linux: source activate new_env