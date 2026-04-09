### Data Cleaning Summary

- Removed duplicate records using drop_duplicates()
- Handled missing values:
  - Filled 'director' with 'Unknown'
  - Filled 'cast' with 'Not Available'
  - Filled 'country' with 'Unknown'
  - Filled 'rating' with 'Not Rated'
- Standardized column names to lowercase with underscores
- Converted 'date_added' to datetime format
- Ensured correct data types (e.g., release_year as integer)
- Cleaned text formatting (trimmed spaces, standardized values)

Final dataset is clean and ready for analysis.
