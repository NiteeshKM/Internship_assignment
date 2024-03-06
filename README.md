# Internship_assignment
Approach:
The code reads the input CSV file into a pandas DataFrame and iterates through each row to transform the data into a row-based historical versioning format.
For each record, it derives the 'Effective Date' and 'End Date' based on the compensation dates and ensures the 'End Date' is one day before the next 'Effective Date' to avoid overlap.

Assumptions:
It is assumed that the input data contains valid date formats for compensation and review dates
It is assumed that the 'Variable Pay' and 'Tenure in Org' fields are not available in the input data and assigns them default values of 0.0.
