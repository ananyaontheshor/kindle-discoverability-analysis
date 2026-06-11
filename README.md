# Does Price Determine What Gets Read?
## Kindle Marketplace Discoverability Analysis

## Question
Does pricing model — specifically Kindle Unlimited inclusion and price tier — 
structurally determine which books get discovered on Amazon?

## Dataset
133,102 Amazon Kindle book listings (2023) from Kaggle.  
Source: https://www.kaggle.com/datasets/asaniczka/amazon-kindle-books-dataset-2023-130k-books

## Key Findings
- Kindle Unlimited titles have a 5x higher bestseller rate than paid titles
- KU titles receive 25x more reader reviews than paid titles (median 50 vs 2)
- 47% of all Kindle books have zero reviews — effectively invisible to readers
- Under $5 is the engagement sweet spot — higher median reviews than even free titles
- LGBTQ+ eBooks and genre fiction are most algorithmically advantaged (KU penetration 70.9%)
- Science, Math, and academic categories are structurally disadvantaged (KU penetration 6.5%)

## Core Insight
Kindle Unlimited creates a two-track discovery system. Genre fiction authors 
in KU get 5x the bestseller rate and 25x the reader engagement of paid titles. 
Non-fiction and academic authors compete at a structural disadvantage regardless 
of quality or price.

## Tools
Python, pandas, matplotlib, seaborn, Tableau