# Working with Data

A collection of Jupyter notebooks where I practise data analysis with Python and pandas. Each notebook takes a dataset, cleans it up and answers questions about it.

This is a work in progress. I'm adding new notebooks and datasets as I learn new techniques.

## Notebooks

### Amazon sales analysis
`amazon_sales_data.ipynb` · data: `amazon_sales_data 2025.csv` (250 orders)

- Loads a year of Amazon sales orders
- Filters out cancelled orders
- Ranks customers by their total spend
- Finds the date range the data covers

## Built with

- Python 3
- [pandas](https://pandas.pydata.org/)
- Jupyter Notebook

## Running the notebooks

You need Python 3, pandas and Jupyter:

```
pip3 install pandas notebook
jupyter notebook
```

Then open a notebook from the list in your browser. Keep each CSV file in the same folder as its notebook.

You can also read the notebooks, including their output, directly on GitHub without installing anything.

## What I'm learning

- Loading CSV data into a pandas DataFrame
- Filtering rows based on their text values
- Grouping, totalling and sorting data with `groupby`
