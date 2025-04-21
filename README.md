# pandera_tutorial 
Pandera Tutorial for BD-STEP Fellows

## Python Packages Needed
- notebook 
  - jupyter notebook interface for interactive demo
- pandas
  - dataframe package
- pandera
  - data validation package

### Need to install pandera[io] to read/write schemas

- If installing via requirements.txt fails can use pip manually as follows:
        
        pip install pandera[io]

## VS Code Extensions Used in Demo

- Need these extensions for VS Code if you want to run .ipynb in VS Code"
    - Python
    - Jupyter (to allow interactive cells in .py files)
    - Notebook

## Data Types for schema for titanic dataset

- survived: int
- pclass: int
- name: str
- sex: str
- age: float
- fare: float
- sibsp: int 
  - note that this is # of siblings/spouses this passenger has onboard
- parch: int 
  - note that this is # of parents/children this passenger has onboard