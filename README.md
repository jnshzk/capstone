# capstone

### DEMOGRAPHIC file 

Field	| Description
--- | --- 
LALVOTERID	| Permanent and unique ID generated by L2 for a single voter
Residence_Addresses_City	 |
EthnicGroups_EthnicGroup1Desc	| European', 'Likely African-American','Hispanic and Portuguese', 'East and South Asian', 'Other'
Voters_OfficialRegDate	| As reported by election authority.
CommercialData_Education	|
CommercialData_EstimatedHHIncome	|
CommercialData_EstimatedHHIncomeAmount	|
FECDonors_NumberOfDonations	|integer representing total number of federal donations made over the last four election cycles
FECDonors_TotalDonationsAmount	|sum of donations over last four election cycles
Voters_BirthDate	| As reported by election authority or matched in from commercial sources.  The format is 99/99/9999"; note that in some cases where year of birth only is available

### VOTEHISTORY file 

Field	| Description
--- | --- 
LALVOTERID | Permanent and unique ID generated by L2 for a single voter
Consolidated_Primary_\<date\>	| Election type followed by date
Local_or_Municipal_\<date\>	| Election type followed by date
General_\<date\>	| Election type followed by date
