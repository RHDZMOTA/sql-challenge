# SQL Challenge

Context
-------

There are two csv-files in the `data` directory:

-   `data/country-happiness.csv` : contains the happiness index for each country
-   `data/wine-price.csv` : contains wine pricing data

Challenge
---------

### Upload datasets

1.  Using the database engine of your choice, create two tables for both csv-files in the `data` directory and ingest the file contents.

### Happiness stats

1.  What's the `max`, `min` and `average` happiness score?

2.  Show a table with the happiness rank and score of the G7 countries (i.e., `Cananda`, `France`, `Germany`, `Italy`, `Japan`, `United Kingdom`, `United States`).

### Wine stats

Note: Limit the output to 10 rows.

1.  How many wines are register per `country`?

2.  What is the average wine `price` per `province`?

### Final analysis

1.  What's the average wine-price of the countries with happiness $score > 7.0$?

2.  Create a csv-file named `output.csv` that contains the country name, rank, score, min-price, average-price, and max-price. The table must be in increasing rank order.
