# AI Overviews and Wikipedia Pageviews

## Overview

This project explores whether the launch of Google AI Overviews was associated with changes in traffic to selected English Wikipedia articles.

The analysis uses publicly available data from the Wikimedia Pageviews API and demonstrates a fully reproducible workflow for collecting, validating, and exploring Wikipedia pageview data.

## Research Question

Did the launch of Google AI Overviews reduce traffic to selected Wikipedia articles?

## Dataset

- Wikimedia Pageviews API
- 15 English Wikipedia articles
- Daily pageviews
- Study period: May 14, 2023 – November 14, 2024

## Workflow

- Treatment group selection
- Data collection from the Wikimedia API
- Data quality checks
- Exploratory data analysis
- Discussion of methodological limitations

## Main finding

The exploratory analysis did not reveal convincing visual evidence of an immediate change following the launch of Google AI Overviews.

More importantly, the project highlights an important limitation of the available data: article-level exposure to AI Overviews cannot be directly observed using the Wikimedia Pageviews API alone.

## Repository

- `ai_overviews_wikipedia_pageviews.ipynb`
- `raw_pageviews_data.csv`
- `treatment_group_selection.xlsx`

## Tools

- Python
- Pandas
- Matplotlib
- Wikimedia Pageviews API
