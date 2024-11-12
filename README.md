# Customer Purchase Behaviour Analysis using Association Rule Mining on Restaurant Sales Data

This project analyses customer purchase behavior in a restaurant setting using association rule mining techniques. It processes sales data to identify patterns and relationships between products purchased together.

## Prerequisites

- Python 3.7+
- Jupyter Notebook

## Required Libraries

- pandas
- numpy
- seaborn
- matplotlib
- sklearn
- mlxtend
- networkx
- squarify

You can install these libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn mlxtend networkx squarify
```

## Project Structure

The project consists of a single Jupyter notebook file and several CSV data files:

- `Customer_Purchase_Behaviour_Analysis.ipynb`: The main Jupyter notebook containing all the analysis code.
- `Catalogo.csv`: Catalog data
- `Compra.csv`: Purchase data
- `CompraItem.csv`: Purchase item data
- `Produto.csv`: Product data
- `Fornecedor.csv`: Supplier data
- `GrupoProduto.csv`: Product group data
- `Usuario.csv`: User data
- `Venda.csv`: Sales data
- `Venda_random.csv`: Random sales data
- `VendaItem.csv`: Sales item data
- `VendaItem_random.csv`: Random sales item data

Ensure all these files are in the same directory as the Jupyter notebook.

## Running the Analysis

1. Open the Jupyter notebook `Customer_Purchase_Behaviour_Analysis.ipynb`.
2. Run each cell in order from top to bottom.

## Analysis Steps

The notebook performs the following steps:

1. Data Loading and Cleaning
2. Exploratory Data Analysis on Sales Data
3. Transaction Analysis
4. Association Rule Mining using Apriori and FP-Growth algorithms
5. Hyperparameter Analysis
6. Focused Analysis for a Specific Emp (Emp 1)

## Results

The analysis provides insights into:

- Most frequently sold products
- Sales patterns over time
- Customer purchase behavior
- Product associations and rules

Key visualizations include:

- Daily sales trends
- Top selling products
- Product co-occurrence heatmaps
- Association rule metrics comparisons

## Notes

- The analysis uses a subset of the full dataset to manage computational resources. You can adjust the data sample size in the notebook if needed.
- Hyperparameters for association rule mining are set conservatively. You may need to adjust these based on your specific dataset and analysis goals.

## Future Work

- Implement more advanced filtering techniques for high-frequency items
- Explore seasonal trends in product associations
- Develop a recommendation system based on the association rules

