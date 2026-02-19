# XRP Model Project

## Run the notebook

### 1) Create and activate a virtual environment

python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip

### 2) Install dependencies

pip install -r requirements.txt

### 3) Install this project

pip install -e .

### 4) Open in VS Code

code .

Select the .venv interpreter inside VS Code.

### OpenMP error workaround (if needed)

export KMP_DUPLICATE_LIB_OK=TRUE
