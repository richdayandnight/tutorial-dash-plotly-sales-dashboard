# tutorial-dash-plotly-sales-dashboard

## Data

- Supermarket sales by Aung Pyae
- [downloaded from a public dateset hosted on Kaggle](https://www.kaggle.com/aungpyaeap/supermarket-sales)

## Configure Environment

1. `pip install -r requirements.txt`
2. `source venv/bin/activate`

## Configure Environment from Scratch

1. Create a project folder
2. Create a virtual environment (python 3 and above)
   - Install pip if you have no pip `pip install virtualenv`
   - Create virtual environment named `venv` : `virtualenv -p python3 venv`
   - install requirements
     - pip install dash==1.13.4 or pip install dash (installs latest version)
     - pip install pandas==1.0.5