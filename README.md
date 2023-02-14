# Make Reports

In this repository is the notebook with which the reports have been working specifically for the BCP, however, this repo is under construction, whose final objective is to obtain a project that generates semi-automatically or automatically the reports on the classifier performance.

For this, a random sample of 663 transactions must first be made, which must then be manually labeled by the user. Then two extra fields must be added, "true_category" and "similarity".

For the moment, this new table will be consumed by the notebook of this repository and will create the graphs and the calculation of the necessary metrics that will go into the NOTION report of the company.

The data structure must be the following to use this repository:

| id   | user_id  | ... | description                             | category_name            | true_category            | similarity |
|------|----------|-----|-----------------------------------------|--------------------------|--------------------------|------------|
| 1234 | 1234abc  | ... | Pago YAPE a 194****                     | Transferencias y Retiros | Transferencias y Retiros | 1          |
| 5678 | 5678abcd | ... | VENDOMATICA            CALLAO        PE | Salud y Bienestar        | Shopping                 | 0          |
| ...  | ...      | ... | ...                                     | ...                      | ...                      | ...        |

Where "the_category" is the true category of the transaction and "similarity" only reflects if there is similarity between the "category_name" and "true_category".


This repository is under development..., always check for updates.

