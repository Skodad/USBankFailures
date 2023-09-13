# USBankFailures
Analyzing the Bank Failures in the US from 1980-2023.

## Objective
The main goal was to look at all the information regarding Bank closures in the US to determine what commonalities existed amongst the failed banks.  This included the location of the banks, size (Assets, Deposits and Estimated Losses), date of the failure, transaction type that was undertaken at failure and charter class.  This could help determine what risk factors to look for so that all stakeholders, including shareholders, employees, clients and regulators, will know the risks involved and what potential risk factors to look for at other financial institutions.

## Data
The Data provided by the FDIC website included the following on Bank Failures and Assistance Data:

- Certification Number
- Charter Class
- City Location
- State Location
- Estimated Losses ('000s US$)
- Total Assets ('000s US$)
- Total Deposits ('000s US$)
- Date of Failure
- FIN
- ID
- Bank Name
- Insurance Fund
- Transaction Type of Resolution
- Resolution Type

## Folders
The following Folders are provided for the analysis:

- **Datasets**: Contains the original and prepared data.  While only one version of the cleaned data was used, there were other two other forms of the data that were prepared, but not used.  The cleaned version consisted of removing 639 lines, all Pre-1980, as Estimated Losses were not provided for these institutions.
- **Project**: Contains the project brief, as well as a list of sites that were used to source various datasets that were considered.
- **Scripts**:  Contains all the Python coding involved for the project.  

