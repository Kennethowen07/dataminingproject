# Global Sustainable Energy Insights

Exploratory Data Analysis on global sustainable energy data from 2000 to 2020. Focused on SDG 7: Affordable and Clean Energy.

## About

We analyzed how electricity access, renewable energy use, energy efficiency, and economic relate to each other across 159 countries (reduced from 176) over 20 years. The notebook covers data cleaning (drop and imputation), visualization, and insights

## Dataset

Source: [Global Data on Sustainable Energy (2000-2020)](https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy) by Ansh Tanwar on Kaggle.

After cleaning, we kept 8 columns: Entity, Year, Access to Electricity, Renewable Share, Energy Intensity, Energy per Capita, GDP Growth, and GDP per Capita which the descriptions are:

| Column | Description |
|---|---|
| Entity | Country name |
| Year | Year of observation (2000–2020) |
| Access to Electricity | % of population with access to electricity |
| Renewable Share | % of renewable energy in total final energy consumption |
| Energy Intensity | Energy used per unit of GDP (MJ/$2017 PPP GDP) |
| Energy per Capita | Primary energy consumption per person (kWh/person) |
| GDP Growth | Yearly GDP growth rate (%) |
| GDP per Capita | GDP per person (USD) |

## How to Run

Install dependencies:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook notebook.ipynb
```

Then run all cells.

## Files

- notebook.ipynb - main notebook
- requirements.txt - technical requirements
