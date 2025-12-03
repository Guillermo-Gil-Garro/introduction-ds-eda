# introduction-ds-eda
Exploratory Data Analysis of a trading card dataset (Python, pandas, visualization).


# Exploratory Data Analysis – Trading Card Dataset

This repository contains an exploratory data analysis (EDA) of a trading card dataset, focused on understanding the distribution of card attributes, release patterns, and relationships between different features.

The goal of this project is to practice end-to-end data exploration using Python, from loading and cleaning the data to generating insights and visualizations that could be useful for product, design or game-balance decisions.

## Quick Look

Some visual summaries from the EDA:

<p align="center">
  <img src="img/cards_by_color.png" width="45%">
  <img src="img/rarity_year.png" width="45%">
</p>

---

## 1. Dataset

- **Type:** Trading card game dataset (one row per card)
- **Examples of variables:**
  - Card name and text
  - Card type / category
  - Mana or cost-related fields
  - Power/toughness or similar stats
  - Rarity and set information
  - Release date/year

> Note: The dataset is used purely for educational purposes in the context of a Data Science Master's program.

---

## 2. Objectives of the EDA

The analysis focuses on:

1. Understanding the distribution of key numerical and categorical variables.
2. Exploring how card characteristics vary across sets and over time.
3. Identifying patterns related to rarity, cost and power-level variables.
4. Detecting potential data-quality issues (missing values, inconsistencies, outliers).

---

## 3. Tools and Technologies

- **Language:** Python
- **Main libraries:**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn` (if used)
- **Environment:** Jupyter Notebook / VS Code

---

## 4. Repository structure

- `eda_mtg_cards.ipynb` – main notebook with the full EDA.
- `data/` (optional) – original dataset or instructions to download it.
- `img/` (optional) – exported plots used in the analysis.

---

## 5. Main insights (summary)

Some examples of questions explored in the notebook:

- How are key stats and costs distributed across the card pool?
- How do card characteristics evolve over different sets or release years?
- Are there noticeable patterns in rarity vs. stats or cost?
- What kind of outliers or unusual cards appear in the dataset?

For detailed visuals and numerical results, see the notebook:
`eda_mtg_cards.ipynb`.

---

## 6. Next steps / possible extensions

- Build simple predictive models (e.g. rarity or type classification).
- Cluster cards based on stats or text features.
- Create interactive dashboards to explore the dataset.

---

## 7. Author

Project developed by **Guillermo Gil Garro** as part of his learning path in **Data Science**.
