## Overview

This contains the code and data used in study 3 of my dissertation, an analysis of US federal agency organizational structures. 

The majority of the data is Fedscope data, which I have downloaded from https://www.fedscope.opm.gov/ and renamed with the year. This data undergoes substantial processing in the analysis to be converted from millions of per-position data to the much smaller per-agency dataframe.

Most of the supplementary materials are in the dissertation, but this repository does include the a spreadsheet which contains:
1. Agency missions that are coded by the Kim-Lowi policy power type;
2. The Code of Federal Regulations that applies to each agency. 

This spreadsheet (code_fed_reg_agency) is imported into the data analysis as a CSV to retrieve these agency-code pairs, and also to process the CFR lines as rule counts per agency.