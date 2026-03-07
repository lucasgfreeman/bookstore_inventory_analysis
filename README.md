README

# Bookstore Inventory Analysis

This project analyzes my early bookstore inventory of 522 books to explore:

- Distribution of books by genre
- Average cost per book by genre
- Cost by acquisition method (Donation, Library Sale, Thrift)

## Files

- `data/Bookstore_Inventory.csv` – the dataset
- `notebooks/library_analysis.ipynb` – Python notebook with all analysis
- `visuals/` – saved charts from the analysis
- `presentations/Bookstore_Inventory_Analysis_Presentation.pdf` - Visual presentation with ananlysis and findings

## Context & Caveats

- Total book count is likely dependent on the size of the leased space.
- Acquisition costs reflect bulk purchase averages; format (hardcover vs. paperback) not assessed.
- Analysis is focused on genres, acquisition costs, and acquisition methods to identify opportunities for genre diversity and cost-efficiency.
- No sales data yet; still in inventory acquisition stage.

## Insights

- About a quarter of inventory so far is history and military books.
- While some genres are underrepresented, inventory standards vary by bookstore, location, and reader interest.
- Mystery, romance, and literary fiction acquisitions exceeded target acquisition cost of $0.50/book. 
- History and military books, though abundant, were predominantly donated.
- Mystery, romance, and literary fiction have been heavily sourced through thrifting, though these genres can also be obtained through library sales or donations, offering multiple sourcing options.
- Thrifting far exceeded the $0.50 per book acquisition goal, while library sales were roughly on track.

## Key Takeaways

- Thrifting may fill gaps in underrepresented genres or high-margin titles, but should not be the primary sourcing method for used books.
- Continue leveraging donations and library sales, which provide cost-efficient acquisitions.
- Explore additional sourcing options, such as  yard sales, estate sales, online purchases, or direct from individuals.
- Consolidating some categories (e.g. self-help with psychology) may fill out emptier shelving and balance genre groups.
- Current strategy is robust to outlier donations, suggesting scalability—efficient acquisitions remain possible even if donations shift.

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

- Tableau Viz: (https://public.tableau.com/app/profile/lucas.freeman6945/viz/Bookstore_Inventory_Project/Sheet1)



