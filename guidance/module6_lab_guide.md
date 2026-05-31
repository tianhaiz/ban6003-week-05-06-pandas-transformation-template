# Module 6 Lab Guide: String and Categorical Data Transformation

**BAN 6003: Data Management and Analytics Integration**

This module gives messy strings and categorical variables their own focused practice. You will work with a small customer contact dataset so that inconsistent labels, spacing, casing, and simple parsing issues are easy to see.

## Lab File

Complete:

`module6_string_categorical_guided_lab.ipynb`

## Dataset

Use:

`data/messy_customer_contacts.csv`

## GitHub Classroom Assignment Link

This module is part of the Module 5-6 assignment package. Canvas will provide the GitHub Classroom invitation link if you have not already accepted this package:

**GitHub Classroom invitation link:** [to be added]

If you already accepted the Module 5-6 assignment, return to the same personal assignment repository and reopen your Codespace. If the repository does not open or GitHub says you do not have access, check the GitHub notifications inbox in the upper-right corner of GitHub, or go to `https://github.com/notifications`, and accept any pending repository or organization invitation from GitHub Classroom.

## What You Will Practice

You will practice standardizing casing and spacing, removing or replacing simple punctuation, using `.str.contains()` to create a flag, using `.str.split()` for simple parsing, recoding categories with `.map()` and `.replace()`, and explaining the assumptions behind recoding decisions.

## Recommended Workflow

1. Open the notebook in GitHub Codespaces.
2. Select the `base` kernel if prompted.
3. Run the setup cells.
4. Inspect the messy categorical values before cleaning.
5. Work through the string cleaning examples.
6. Complete the Your Turn exercises.
7. Write the short reflection on one recoding decision.
8. Save, commit, and push your work.

## What to Pay Attention To

Category recoding is an analytical decision. Ask whether two labels truly mean the same thing, whether any values are ambiguous, and whether your cleaned categories would be understandable to someone else.

## Minimum Completion Checklist

Before submitting, make sure:

- You cleaned name, state, contact method, customer segment, and product fields.
- You created a text-based flag.
- You used `.str.split()` for simple parsing.
- You completed the Your Turn exercises.
- You explained one recoding decision.
- You saved, committed, and pushed your work.
