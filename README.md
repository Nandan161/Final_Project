# Credit Card Fraud Detection Dataset

This dataset contains transactions made by credit cards in September 2013 by European cardholders. The dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. It is highly unbalanced, with the positive class (frauds) accounting for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, the original features and more background information about the data are not provided. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction amount. 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

The dataset is available for download from the [Kaggle website](https://www.kaggle.com/mlg-ulb/creditcardfraud).

## Files

- `creditcard.csv`: The dataset file containing credit card transactions data.

## Data Columns

- `Time`: Number of seconds elapsed between this transaction and the first transaction in the dataset
- `V1-V28`: PCA transformed features
- `Amount`: Transaction amount
- `Class`: The target variable where 1 indicates fraud and 0 indicates non-fraudulent transactions

## Dataset Statistics

- Number of Instances: 284,807
- Number of Attributes: 31 (including the target variable 'Class')

## Usage

You can use this dataset to:

- Explore the characteristics of credit card transactions.
- Develop and validate fraud detection models using machine learning algorithms.
- Analyze transaction patterns and anomalies.

## Citation

The dataset was collected and analyzed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. Please cite the following study when using the dataset:

Andrea Dal Pozzolo, Olivier Caelen, Reid A. Johnson, and Gianluca Bontempi. Calibrating Probability with Undersampling for Unbalanced Classification. In Symposium on Computational Intelligence and Data Mining (CIDM), IEEE, 2015.

## License

The dataset is made available under the Open Database License: http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/.

## Acknowledgements

The authors would like to thank the Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection for providing the dataset.

