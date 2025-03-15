# Web Scraping Product Data from Mercado Libre

This Jupyter Notebook scrapes product data from Mercado Libre, filters it based on price, and exports the results to an Excel file.

## Requirements

1.  Python 3.7 or higher.
2.  Install the required Python packages using pip:
    ```bash
    pip install -r requirements.txt
    ```
3.  Execute the jupyter notebook.

## How to use

1.  **Install Dependencies:** Run `pip install -r requirements.txt` to install the required Python packages.
2.  **Open the Notebook:** Open the Jupyter Notebook file.
3.  **Run the Notebook:** Execute the notebook cells sequentially.
4.  **Verify Data:** The scraped and filtered product data will be saved to an Excel file named `products.xlsx` in the same directory.
5.  **Customize:**
    * Modify the `query` and `base_url` variables in the first code cell to scrape data from a different website or for a different product category.
    * Adjust the price filtering conditions in the `filter_and_sort_data` function to suit your needs.
    * Change the output filename by modifying the `filename` parameter in the `export_to_excel` function.