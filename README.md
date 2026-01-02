# Association Rule Mining on FAO Food Consumption Data

This project analyzes individual food consumption data from the FAO/WHO GIFT platform
using association rule mining techniques.

## Dataset
- Source: FAO/WHO GIFT – Individual Food Consumption Data
- Country: Romania (2012, DIETA PILOT Adults Study)
- Unit of analysis: person-day food consumption

## Methods
- FP-Growth (main algorithm)
- Apriori (comparative baseline)
- Metrics: support, confidence, lift

## Files
- `analysis_fao_association_rules.ipynb` – full analysis and code
- `output/` – generated frequent itemsets, rules, and benchmark results

## Requirements
- Python 3
- pandas
- mlxtend

## How to run
Open the notebook and run all cells sequentially.
