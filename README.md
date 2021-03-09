# CMD Trade

Script for tansforming trade data.

Transform takes 2 input xlsx files, remove any previous xlsx files so there is no confusion in which spreadsheet is picked up. The input files are found from the ONS website:

imports - https://www.ons.gov.uk/economy/nationalaccounts/balanceofpayments/datasets/uktradecountrybycommodityimports

exports - https://www.ons.gov.uk/economy/nationalaccounts/balanceofpayments/datasets/uktradecountrybycommodityexports

Place the input files in the same directory as the script or alternatively change the location variable in transform.ipynb to match the file location.

1 output files is created
- v4-trade.csv

The transform only requires use of base level packages.

The transform takes around 5 minutes to complete.
