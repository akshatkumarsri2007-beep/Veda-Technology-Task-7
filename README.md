# Veda Technology Task 7 Report
# First Chart Story: Turning Numbers into a Narrative

Data Analytics Internship Task — Veda Technology
Submitted by: Akshat Srivastava

## Overview

This project takes the classic Iris flower dataset and builds a small set of charts that each answer one specific question. The goal is not just to make charts, but to pick the right chart type for each question, label it clearly, and tie the individual charts together into a single narrative.

## Dataset

- **Name:** Iris Dataset
- **Size:** 150 rows, 5 columns
- **Columns:** `sepal_length_cm`, `sepal_width_cm`, `petal_length_cm`, `petal_width_cm`, `species`
- **Species:** setosa, versicolor, virginica (50 samples each, perfectly balanced)

## Tools Used

- Microsoft Excel / WPS Office (Pivot Tables and Pivot Charts)
- Word / PDF for the final report

## Charts and Questions

| # | Chart Type | Question Answered |
|---|------------|--------------------|
| 1 | Bar Chart | Which species has the largest petals? |
| 2 | Pie Chart | What is the species composition of the dataset? |
| 3 | Line Chart | How do average measurements change across species? |
| 4 | Bar Chart | Which measurement varies the most across species? |

## Key Findings

- The dataset is perfectly balanced, with each species making up exactly one third of the samples.
- Virginica has the largest average petal length, followed by versicolor, then setosa.
- Petal length and petal width increase sharply from setosa to virginica, while sepal measurements stay comparatively flat.
- Petal length has the widest range across species, making it the single most useful measurement for telling the three species apart.

## Approach

1. Explored the raw dataset to understand its structure and columns.
2. Built a pivot table to calculate average petal length per species, then charted it as a bar chart.
3. Built a pivot table to count samples per species, then charted the composition as a pie chart.
4. Built a pivot table with all four average measurements per species, then charted the trend as a line chart.
5. Calculated the range (max minus min) of each measurement across species and charted it as a bar chart.
6. Labeled every chart with a descriptive title, axis titles, and a one-line takeaway.
7. Wrote a short summary connecting all four charts into a single narrative.

## Files

- `iris_dataset.csv` — the raw dataset used for this task
- `Task7_Chart_Story_Akshat.pdf` — final report with all charts, takeaways, and summary
- `Task_7_Veda_Technology.xlsx` — the Excel workbook with pivot tables and charts

## Interview Questions (Covered)

- When would you choose a bar chart over a line chart?
- Why are pie charts often discouraged in professional reporting?

These are addressed in practice through the chart choices made above: bar charts were used to compare discrete categories (species, measurement ranges), while a line chart was used to show a trend across an ordered sequence of species. The pie chart here works only because there are just three, evenly sized categories; with more categories or less even splits, a bar chart would communicate the same information more precisely.
