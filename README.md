README

# Bookstore Inventory Analysis

This project analyzes my personal bookstore inventory of 522 books to explore:

- Distribution of books by genre
- Average cost per book by genre
- Cost by acquisition method (Donation, Library Sale, Thrift)
- Top authors and most-copied books

## Files

- `data/Bookstore_Inventory.csv` – the dataset
- `notebooks/library_analysis.ipynb` – Python notebook with all analysis
- `visuals/` – saved charts from the analysis
- `slides/Library_Insights.pdf` – optional presentation summarizing insights

## Insights

- Most books are in History/Military and Literary genres.
- Library sales are cheaper than thrift stores on average.
- Some authors and books appear multiple times, reflecting duplicates in the inventory.

## Data Cleaning & Preparation

Before analysis, the dataset was cleaned as follows:

- Ensured all donations have a cost of $0.  
- Checked and filled missing values for Author, Book Title, Publisher, and Genre where applicable.  
- Removed or standardized extra whitespace and formatting inconsistencies.  
- Converted Cost_of_Acq from string to numeric for analysis. 
- Verified duplicate titles and handled them in visualizations and aggregations.

## How to Run

1. Open the notebook in Jupyter, VSCode, or another Python IDE that supports notebooks.
2. Ensure Python 3 and these libraries are installed: `pandas`, `matplotlib`, `seaborn`.
3. Run all cells to reproduce the charts and tables.

## Optional

- Tableau dashboards or other interactive visuals can be linked here.
- 
## Optional Visuals

- Tableau dashboards: saved in `visuals/tableau/`
- Presentation slides: saved in `slides/`
