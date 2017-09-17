# Code/01\_Data\_Acquisition_and_Understanding

For source code files associated with data preparation. Data preparation includes one or more of the following steps (not exhaustive):

- Data ingestion
- Data cleanup
- Data reduction
- Data exploration 
- Data visualization

For further information on data feature and defnintion, you can read this document in TDSP public GitHub repo [(link)](https://github.com/Azure/Azure-TDSP-ProjectTemplate/blob/master/Docs/Data_Report/Data%20Defintion.md). And, for what information may be present in a data summary report, you can read this document [(link)](https://github.com/Azure/Azure-TDSP-ProjectTemplate/blob/master/Docs/Data_Report/DataSummaryReport.md).

## Code file documentation

### DataPreparation.py:
    Purpose: download and prepare data
    Language: Python
    How it gets used: Used in Code\01\_Data\_Acquisition\_and_Understanding\Main.py
    downloaddata: download training and test data from the web to local

### Main.py:
    Purpose: call function in DataPreparation.py to download data
    Language: Python