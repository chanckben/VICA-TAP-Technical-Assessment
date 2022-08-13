# VICA TAP Technical Assessment

This repository contains code in fulfilment of the aforementioned assessment. Any assumptions made about the requirements of the assessment are listed below:

## Task 1
- "Data quality" refers to the presence or absence of outliers, missing values, invalid data, etc. After examining the data quality, we can perform data preprocessing to fix data quality issues.
- "Identifying correlations between data attributes" refers to comparing the distributions of the attributes and checking which attributes are dependent on each other. It is also an implicit step of feature selection.
- "Older people" refers to individuals aged 45 or older as defined by the `is45OrOlder` column in the dataset.
- The factors affecting whether insurees renew their policies are limited to the attributes given in the dataset.

## Task 2
- Since the data structure is already provided in the PDF, "data modelling" is assumed to refer to defining the schema validation rules for the collection and transforming the values in the dataset to the correct types.
- "Environment setup" refers to setting up MongoDB on my local system. I am unable to show what happens on my computer but I provided steps I took to set up MongoDB in the Jupyter notebook.
- "Database connection" refers to using MongoClient in PyMongo to make a connection with a MongoDB instance running on `localhost` on port 27017.
