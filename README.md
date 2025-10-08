# Netflix Content Trends Analysis

Analyze Netflix’s content trends (Movies vs TV Shows, genres, countries) from 2008–2021 using Python and Jupyter/Colab.

This repository contains:
- Netflix_Content_Trends_Analysis.ipynb — the main analysis notebook
- Netflix Dataset.csv — the dataset used by the notebook

Open the notebook directly in Google Colab and follow the prompts to upload the dataset (the notebook already includes an upload cell).


## Open in Google Colab

Replace `YOUR_USERNAME` and (optionally) repository name if you use a different one, then click the badge:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/Netflix_Content_Trends_Analysis/blob/main/Netflix_Content_Trends_Analysis.ipynb)


## How to use in Google Colab

1. Push this folder to a GitHub repository (see the steps below).
2. Click the Colab badge above (after updating the URL with your GitHub username/repo name) or open Colab → File → Open notebook → GitHub → paste your repo URL.
3. Run the notebook cells. When prompted, use the upload widget to upload `Netflix Dataset.csv` from this repository.

Note: Colab does not automatically include repository files unless explicitly downloaded; the notebook’s upload cell is already set up for convenience.


## Local execution (optional)

Run the analysis locally with a Python environment.

- Prerequisites: Python 3.8+
- Create and activate a virtual environment, then install dependencies

Windows (CMD):
- python -m venv .venv
- .venv\Scripts\activate
- pip install -r requirements.txt

macOS/Linux (bash):
- python3 -m venv .venv
- source .venv/bin/activate
- pip install -r requirements.txt

Then launch Jupyter and open the notebook:
- jupyter notebook

Ensure `Netflix Dataset.csv` is in the same directory as the notebook.


## Repository structure

- Netflix_Content_Trends_Analysis.ipynb — main notebook
- Netflix Dataset.csv — dataset used by the notebook
- README.md — this guide
- requirements.txt — Python dependencies for local execution


## Publishing to GitHub (quick guide)

- Create a new repository on GitHub (e.g., `Netflix_Content_Trends_Analysis`).
- From this folder, initialize Git (if not already) and push:
  - git init
  - git add .
  - git commit -m "Initial commit: Netflix Content Trends Analysis"
  - git branch -M main
  - git remote add origin https://github.com/YOUR_USERNAME/Netflix_Content_Trends_Analysis.git
  - git push -u origin main
- Update the Colab badge link in this README to point to your repo.


## Notes

- The notebook relies on common data science libraries available by default in Google Colab (pandas, numpy, matplotlib, seaborn). A `requirements.txt` is provided for local runs.
- If you later host the dataset elsewhere (e.g., a direct raw file URL in GitHub), you can modify the notebook’s data loading cell to read the CSV from that URL instead of using the upload widget.