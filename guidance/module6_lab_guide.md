# Module 6 Lab Guide: String and Categorical Data Transformation

**BAN 6003: Data Management and Analytics Integration**

This module gives messy strings and categorical variables their own focused practice. You will work with a small customer contact dataset so that inconsistent labels, spacing, casing, and simple parsing issues are easy to see.

## Lab File

Complete:

`module6_string_categorical_guided_lab.ipynb`

## GitHub Repository and Running Environment

This module is part of the Module 5-6 package. Use the same repository you created from this public template repository:

https://github.com/tianhaiz/ban6003-week-05-06-pandas-transformation-template

Continue working in your own repository, not the instructor template. Use Codespaces as the main path, or use your local conda/Jupyter environment if you are comfortable managing it. Make sure your repository is public, or invite `zzz1990771` / `zzz1990771@gmail.com` if it is private. Submit your GitHub repository link through Canvas.

## Dataset

Use:

`data/messy_customer_contacts.csv`


## What You Will Practice

You will practice standardizing casing and spacing, removing or replacing simple punctuation, using `.str.contains()` to create a flag, using `.str.split()` for simple parsing, recoding categories with `.map()` and `.replace()`, and explaining the assumptions behind recoding decisions.

## Recommended Workflow

1. Open the notebook in Codespaces, or in local Jupyter if you are using the optional local path.
2. Select the course Python kernel if prompted.
3. Run the setup cells.
4. Inspect the messy categorical values before cleaning.
5. Work through the string cleaning examples.
6. Complete the Your Turn exercises.
7. Write the short reflection on one recoding decision.
8. Save your work, then commit and push if using GitHub.

## What to Pay Attention To

Category recoding is an analytical decision. Ask whether two labels truly mean the same thing, whether any values are ambiguous, and whether your cleaned categories would be understandable to someone else.

## Minimum Completion Checklist

Before submitting, make sure:

- You cleaned name, state, contact method, customer segment, and product fields.
- You created a text-based flag.
- You used `.str.split()` for simple parsing.
- You completed the Your Turn exercises.
- You explained one recoding decision.
- You saved your work and submitted through Canvas.
