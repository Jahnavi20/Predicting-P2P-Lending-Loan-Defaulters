# Predicting-P2P-Lending-Loan-Defaulters

The business case that we have analyzed is a publicly available data set of a leading European Peer 2 Peer (P2P) lending platform, Bondora. P2P lending risk has been an attractive risk factor to assess a potential borrower’s behavior. P2P lending is a way to raise debt for individuals which is becoming popular for developing countries. 

Our data set includes P2P data from Estonia. This data is an indicator for lenders and various financial institutions to understand trends of borrowers that may lead to them defaulting on a loan. These metrics and trends help researchers for lenders analyze the risk factors most important when selecting potential borrowers. 

What we are predicting using this dataset is the probability that someone will default on a loan, based on if there is a default date present in the data set. We have derived our recommended model based on the predictors in the data set that we have found through visualization and correlation that help derive our categorical target of default date. 

Our dataset initially consisted of 112 columns with 179,235 rows; it has been reduced to 22 columns and 30,591 rows based on pre-processing techniques. Variables that were removed were based on high volume of missing values, lack of predictive power to the target variable and strong correlation between columns through data visualization. Our dataset distribution of ‘1’ for default date at present is 8,520 and 22,071 for ‘0’ which represents no default date.
