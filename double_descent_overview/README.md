# Double descent in machine learning

This repository contains the code and notebook that reproduce the key figures from the accompanying blog post on **double descent**, a fascinating phenomenon observed in modern machine learning models.

## What's Included

- `example.ipynb`: Jupyter notebook that walks through the double descent setup and visualizations
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
python -m venv venv
source venv/bin/activate  # on Linux/Mac
venv\Scripts\activate     # on Windows
```

#### 3. Install dependencies
```bash
pip install -r requirements.txt
```

#### 4. Launch the notebook
```bash
jupyter notebook example.ipynb
```
You can also open it in VS Code, JupyterLab, or another compatible environment.


### Option 2: Run in Google Colab
Don't want to set anything up? You can run the notebook in the cloud via Google Colab with a single click:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/garyuppal/blog-code/blob/main/double_descent_overview/example.ipynb)

Colab will open the notebook and let you run it interactively without installing anything.

### Dependencies
This project uses the following Python packages (see requirements.txt):

- numpy

- matplotlib

- scikit-learn

If you're running the notebook in Colab, these packages will be installed automatically when you run the first code cells (or you can use !pip install -r requirements.txt in a cell if needed).