# sales-analysis

Team repository of the course *Git, Python Environments & Coding Best Practices* (MSA-DATB07-03).
Practice repository for TD3 and TD4 (not graded): see `TASKS.md` for the work of sessions 3 and 4, and `CONTRIBUTING.md` for the rules.

A small Python package that computes revenue figures from `data/sales.csv`.

## Team

<!-- Replace with the names and GitHub user names of your team -->
- Firstname Lastname (@handle)

## Features

- load a sales CSV into a list of typed rows
- total revenue
- monthly revenue

## Running the tests

```bash
python -m pytest
```

## Dependencies

- pytest: runs the tests

## Usage

Install pytest and run the tests:

```bash
python -m pip install pytest
python -m pytest
```

Compute the total revenue of the sales file:

```bash
PYTHONPATH=src python -c "from sales_analysis import load_sales, total_revenue; print(total_revenue(load_sales('data/sales.csv')))"
```
