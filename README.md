# My_project
1. General Structure
Total Records: 500 entries (rows)

Total Features: 5 columns

Missing Values: None (all columns have 500 non-null entries)

2. Column Breakdown & Data Types
model (Object/Text): The name/model of the smartphone (401 unique models).

price (Integer): The price of the smartphone.

rating (Float): The user or expert rating given to the phone (on a scale likely up to 100).

ram_gb (Integer): The RAM capacity specified for the phone.

storage_gb (Integer): The internal storage capacity specified for the phone.

Note on RAM & Storage: In this specific dataset, the ram_gb and storage_gb columns contain exactly identical values for every row. Furthermore, for budget feature phones like the Jio Jiophone 2 and Nokia 8000 4g, the value is listed as 512 (which likely represents 512 MB rather than GB).

3. Key Summary Statistics
Price Distribution:

Average Price: 32,772.16

Minimum Price: 2,999 (Jio Jiophone 2)

Maximum Price: 650,000 (Vertu Signature Touch)

Median Price (50th percentile): 20,990 (indicating that a few ultra-luxury phones pull the average upward).

Ratings Distribution:

Average Rating: 79.35

Minimum Rating: 60.0

Maximum Rating: 89.0 (Achieved by the OnePlus 11 5G, Samsung Galaxy S23 Plus, and Xiaomi 12t Pro 5G)

RAM/Storage Values:

The most common values are 4 GB, 6 GB, and 8 GB.

The unique values present across the dataset are: 1, 2, 3, 4, 6, 8, 12, 16, 18, 512.

4. Brand Popularity (Top 5 Brands)
By extracting the brand name from the model column, the most frequently occurring brands in this dataset are:

Samsung (74 models)

Xiaomi (70 models)

Vivo (53 models)

Realme (47 models)

Oppo (43 models)

5. Notable Extrems
Top 3 Most Expensive Phones:

Vertu Signature Touch — 650,000 (Rating: 62.0)

Huawei Mate 50 RS Porsche Design — 239,999 (Rating: 81.0)

Xiaomi Redmi Mix Alpha — 199,990 (Rating: 80.0)

Top 3 Highest Rated Phones:

OnePlus 11 5G — 54,999 (Rating: 89.0)

Samsung Galaxy S23 Plus — 84,990 (Rating: 89.0)

Xiaomi 12t Pro 5G — 59,990 (Rating: 89.0)
