# Double Descent Demystified: Rethinking Model Complexity in Machine Learning

This repository contains the code that reproduce the key figures from the accompanying blog post [Double Descent Demystified: Rethinking Model Complexity in Machine Learning](https://garyuppal.github.io/posts/double_descent/).

## What's Included

- `main.ipynb`: Jupyter notebook that walks through the double descent setup and visualizations
- `requirements.txt`: List of required Python packages

---

## Run the Notebook

You can either run the notebook locally or in Google Colab.

### Option 1: Run Locally

#### 1. Clone the repository

```bash
git clone https://github.com/garyuppal/blog-code.git
cd blog-code/double_descent_overview
```

#### 2. (Optional) Create a virtual environment
```bash
python -m venv double-descent
source double-descent/bin/activate  # on Linux/Mac
double-descent\Scripts\activate     # on Windows
```

#### 3. Install dependencies
```bash
pip install -r requirements.txt
pip install jupyter ipykernel
```


#### 4. Launch the notebook
```bash
jupyter notebook main.ipynb
```
You can also open it in VS Code, JupyterLab, or another compatible environment.


### Option 2: Run in Google Colab
Don't want to set anything up? You can run the notebook in the cloud via Google Colab with a single click:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/garyuppal/blog-code/blob/main/double_descent_overview/main.ipynb?fresh=true)

Colab will open the notebook and let you run it interactively without installing anything.

### Dependencies
This project uses the following Python packages (see requirements.txt):

- numpy

- matplotlib

- scikit-learn

If you're running the notebook in Colab, these packages will be installed automatically when you run the first code cells (or you can use !pip install -r requirements.txt in a cell if needed).