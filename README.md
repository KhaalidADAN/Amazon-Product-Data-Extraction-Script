"""
Amazon Product Data Extraction Script

This script extracts product details (name, price, rating, and rating count) from an Amazon search results HTML file and saves them into a CSV file using BeautifulSoup and pandas.

Requirements:
- Python 3.x
- Libraries: `beautifulsoup4`, `pandas`
  Install with: `pip install beautifulsoup4 pandas`

Usage:
1. Place the Amazon HTML file in the specified path:
   - Default: C:\\Users\\user\\Dropbox\\PC\\Downloads\\amazon_23.html
   - Change the `file_path` variable in the script to use a different file.

2. Run the script to extract:
   - Product Name
   - Price
   - Rating
   - Rating Count

3. Output CSV:
   - Default save path: C:\\Users\\user\\Dropbox\\PC\\Documents\\amazon_combined_products.csv
   - Modify `output_file` variable to change save location.

Customization:
- Update `file_path` and `output_file` variables for custom paths.

Note:
This script is tailored for Amazon’s HTML structure at the time of writing. Structure changes may require script adjustments.
"""
