# shark_attacks
______________________________________________________________________________

## Purpose:

Sharks have been a target of fascination and fear for milennia.
______________________________________________________________________________

## Methodology:
### Project Directory Layout

    ├── Resources               # Datasource .csv from Kaggle and JSON files stored here for endpoints.
    │   ├── shark_clean.csv     # Shark data ready for Tableau
    │   ├── type_invalid.csv    # Shark data labeled as "Invalid"
    ├── Setup.ipynb             # Python Script for extracting, transforming, and loading data  
    ├── SharkButtons            # Image files created for Tableau Dashboard
    └── README.md               # Readme File
    
 ### Data Source:
 
 Shark Attack dataset found on OpenDataSoft.
 Wrote HTTP requests to OpenDataSoft API endpoint to retrieve 1000 random shark attack incidents.   
 
 ### Procedure:
 
 1. Grabbed desired data using HTTP request and converted dataset into a Pandas Dataframe.
 2. Cut unnecessary fields and performed initial investigation of the data.
 3. Cleaned the dataset:
    a. Cleaned up species: Filled NaN's with "unknown". Looked at unique species listed and compile them into a list. 
       Next, take 
 5. Export the dataset as CSV
 ______________________________________________________________________________
 
  ## Dashboard:
  
  https://public.tableau.com/app/profile/jennifer.shulyak/viz/Shark_Incidents/Dashboard1
  
  
  
  _____________________________________________________________________________
  
  ## Analysis: 
