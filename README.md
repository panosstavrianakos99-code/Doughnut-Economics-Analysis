# Doughnut Economics: Social and Ecological Indicators

This Python project explores how countries and income groups compare on social needs and ecological pressures. It uses indicator data spanning approximately 2000–2022 and organizes the analysis around the Doughnut Economics framing: social shortfall on one side and ecological overshoot on the other.

## Analytical workflow

1. **Prepare and summarize indicators.** Use pandas to filter social and ecological measures, reshape the data into comparison tables, and review indicator coverage and units.
2. **Compare country groups.** Examine ecological overshoot and social shortfall across income groups with grouped visualizations.
3. **Show global patterns.** Build a two-sided sandwich chart and an interactive doughnut chart for selected 2022 global indicators.
4. **Support interpretation.** Present indicator units alongside the visualizations so readers can understand what each measure represents.

## Tools and languages

- **Python** for data preparation and visualization.
- **pandas and NumPy** for filtering, reshaping, and handling indicator tables.
- **Matplotlib** for static charts.
- **Plotly** for the interactive doughnut visualization.
- **IPython display** for rendering notebook tables and interactive content.

## Project files

- `doughnut_economics_analysis.ipynb` — analysis, tables, and visualizations.

## Data and running the notebook

The notebook reads multiple CSV files for indicator values and chart inputs. Place the required CSVs alongside the notebook or update the paths to your data directory. Open the notebook in Jupyter and run the cells from top to bottom after installing the libraries listed above.

## Interpretation

This is descriptive analysis. Indicators differ in definitions, units, and coverage periods, so values should be interpreted within each measure and not treated as directly comparable across unlike units. The visualizations do not establish causal relationships.
