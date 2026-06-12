# kickstarter-sql-analysis
SQL queries created for analyzing a dataset of Kickstarter projects, exploring funding success rates, category popularity, and project outcomes

Kickstarter Project Analysis with SQL

This project analyzes Kickstarter crowdfunding data using SQL queries. The goal is to explore and understand trends related to project funding success and popularity across different Kickstarter categories.
Dataset

The dataset ksprojects includes project-level information such as:

    main_category: The primary category of the project
    backers: Number of backers supporting the project
    pledged: Amount pledged by backers
    goal: Funding goal set by the project creator
    state: Current status of the project (e.g., successful, failed, canceled)

Analysis Questions and Approach

Throughout the project, I explored different questions using SQL, including:

    Category Funding and Success Rates:
    Grouped projects by category to calculate:
        Average funding percentage (pledged / goal) per category
        The total number of projects per category
        Number and rate of successful projects in each category

    Filtering and Sorting Data:
    Used WHERE clauses to filter projects by state and funding criteria, then sorted results using ORDER BY to identify top-performing categories.

    Conditional Logic with CASE Statements:
    Created new columns based on conditions, such as classifying projects by funding status (e.g., fully funded or not).

    Data Formatting:
    Formatted numerical results as percentages with rounding and string concatenation to improve readability.

Dataset can be found here:
https://www.kaggle.com/datasets/kemical/kickstarter-projects?utm_source=openai
