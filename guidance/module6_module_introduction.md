# Module 6 Introduction: String and Categorical Data Transformation

This module focuses on a problem that appears constantly in real business data: messy text and messy categories. A human may know that `Texas`, `TX`, and `tx.` refer to the same state, but Python treats them as different values unless we standardize them.

Messy categorical fields are not just cosmetic problems. They affect counts, summaries, dashboards, and models. If one real category is split across several inconsistent labels, the analysis becomes less trustworthy.

## This Week You Will

- identify inconsistent text labels, casing, spacing, punctuation, and synonyms;
- standardize text using Pandas string methods;
- use `.str.contains()` to create a text-based flag;
- use `.str.split()` for simple parsing;
- recode categories using mapping rules;
- explain the assumptions behind at least one recoding decision.

## Standardizing vs. Recoding

Standardizing makes the same value look consistent. Recoding goes further by grouping values into analysis-ready categories based on a business rule. That distinction matters because recoding changes interpretation. A recoding dictionary is not just code; it is also a decision document.

## Lab Focus

The lab uses a small intentionally messy customer contact dataset. You will clean customer names, state labels, contact methods, customer segments, and product fields, then create flags and grouped categories.

## Project Connection

If your project includes text or categorical fields, begin watching for inconsistent labels and ambiguous categories. When you recode values, write down why certain labels belong together. A good recoding decision is both technically correct and explainable.
