# RefStress
An R markdown file that takes you through the process for finding reference and stress sites

This script was built using R 4.0.2 (Taking Off Again). And rebuilt under R 4.3.0 (Already Tomorrow) to have markdown run more efficiently (_NewMap).

This tool filters reference and stress sites from Virginia and West Virginia EDAS databases, in this script we cast a "wide net" net on 
all the data (n=5292). This initial filter looks at 6 stress parameters that were available for the most sites in the database(s). 

This is just step one of two step process, VDEQ and WVDEP biologists will review the results and help refine the reference and 
stress sites based on their site specific knowledge. WV DEP data was collected between 1999-2017, VDEQ data collections occurred 
from 2008-2020, but the majority was collected between 2012-2019.

This repository contains two different RefStress Markdown documents, one for the Coastal EcoRegions and one for Non-coastal Ecoregions

Least Disturbed (Ref) Filter Parameters Non-Coastal EcoRegions:

1.	DO >8 mg/L
2.	pH >6,<9
3.	Sp Cond < 250 uS/cm
4.	TN <= 1 mg/L
5.	TP <= 0.02 mg/L
6.	Total Habitat > 150

Stress Filters Parameters Non-Coastal EcoRegions:

1.	DO < 7 mg/L
2.	pH <6,>9
3.	Sp Cond > 500 uS/cm
4.	TN >= 2 mg/L
5.	TP >= 0.05 mg/L
6.	Total Habitat <= 120

Least Disturbed (Ref) Filter Parameters for the Coast EcoRegions:

1.	DO > 4 mg/L
2.	pH > 6, < 9
3.	Sp Cond < 200 uS/cm
4.	TN <= 1.5 mg/L
5.	TP <= 0.05 mg/L
6.	Total Habitat > 140


Stress Filters Parameters for the Coast EcoRegions:

1.	DO < 4 mg/L
2.	pH > 6, < 9
3.	Sp Cond > 500 uS/cm
4.	TN >= 3.0 mg/L
5.	TP >= 0.1 mg/L
6.	Total Habitat <= 120
