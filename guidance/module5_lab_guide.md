# Module 5 Lab Guide: Basic Data Transformation with Pandas

**BAN 6003: Data Management and Analytics Integration**

This module focuses on common Pandas transformations. You will use `nycflights13` to filter rows, sort records, select columns, rename fields, create derived variables, and export a transformed dataset.

The main question is:

> How do we turn raw columns and rows into a dataset that is easier to analyze?

## Lab File

Complete:

`module5_basic_transformation_guided_lab.ipynb`


## GitHub Repository and Running Environment

Start from this public template repository:

https://github.com/tianhaiz/ban6003-week-05-06-pandas-transformation-template

Create your own GitHub repository from the template with **Use this template > Create a new repository**. I recommend making your repository public so the instructor can inspect your submission. If you use a private repository, invite the instructor GitHub account `zzz1990771` or the email `zzz1990771@gmail.com` as a collaborator.

You may run the lab in either environment:

- **Recommended for beginners:** GitHub Codespaces from your own repository.
- **Local option:** clone your own repository, activate the `ban6003` conda environment, install `requirements.txt`, and run JupyterLab locally.

Submit your GitHub repository link or a completed ZIP through Canvas.

## What You Will Practice

You will practice `query()`, `sort_values()`, column selection with brackets and `.loc[]`, `.filter()`, `rename()`, `assign()`, simple derived columns, and `to_csv()`.

## Recommended Workflow

1. Open the notebook in Codespaces or local Jupyter.
2. Select the course Python kernel if prompted.
3. Run the setup cells.
4. Work through the filtering, sorting, selecting, renaming, and derived-column examples.
5. Complete each Your Turn section.
6. Export the transformed dataset when prompted.
7. Write the final reflection.
8. Save your work, then commit and push if using GitHub.

## Scope Reminder

This module is about basic transformation. Aggregation, reshaping, joins, SQL, and formal ABT documentation appear later. Focus on making each transformation readable and explainable.

## Minimum Completion Checklist

Before submitting, make sure:

- You loaded `nycflights13.flights`.
- You filtered rows.
- You sorted records.
- You selected useful columns.
- You renamed at least one field.
- You created at least one derived column.
- You exported a transformed file.
- You completed the Your Turn sections and final reflection.
