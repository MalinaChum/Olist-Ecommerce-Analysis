# Ecommerce Logistics Analysis

This repository contains a Jupyter notebook project analysing ecommerce
logistics performance using the public Olist Brazilian ecommerce dataset.

The main focus is understanding how orders move from purchase to delivery,
what drives delivery delays, and how logistics performance relates to
customer satisfaction.

## Repository Contents

- Ecommerce_Analysis_Project.ipynb – main analysis notebook covering:
  - Data loading and cleaning
  - Joining orders, customers, products, sellers and reviews
  - Feature engineering for delivery timelines and KPIs
  - Exploratory data analysis and visualisations
  - Insights on delays and customer review scores

## Getting Started

1. Clone the repository:

	```bash
	git clone https://github.com/MalinaChum/Ecommerce-Logistics-Analysis.git
	cd Ecommerce-Logistics-Analysis
	```

2. (Optional) Create and activate a virtual environment.

3. If a requirements.txt is present, install dependencies with:

	```bash
	pip install -r requirements.txt
	```

4. Open the notebook in VS Code, JupyterLab, or another Jupyter environment
	and run the cells from top to bottom.

## Dataset

The analysis uses the Olist Brazilian ecommerce public dataset, which includes
tables for orders, customers, sellers, products, payments and reviews. These
tables are combined to study logistics behaviour, delivery times and customer
experience.

## Analysis Goals

- Describe end‑to‑end ecommerce delivery timelines
- Measure delivery delays and on‑time performance
- Explore how logistics metrics relate to review scores
- Provide visual insights that can inform logistics optimisation

You can extend this project by adding more features, building predictive
models (for example, delivery time prediction), or turning the analysis into
dashboards for business stakeholders.
