# Election Audit

## Overview

### Purpose
The purpose of this audit was to create a Python script that would pull information from a dataset containing congressional election results.

## Results
The following election outcomes were addressed, and the related codes are provided next to each outcome:
- **Total votes cast:**

    <img src="resources/Results_Vote_Total.png" height=30% width=30% align="left">

    <img src="resources/Results_Vote_Total_Code.png" height=42% width=42%>

- **Breakdown of votes and percentage of total votes for each county:**

    <img src="resources/Results_County_Breakdown.png" height=30% width=30% align="left">

    <img src="resources/Results_County_Breakdown_Code.png" height=60% width=60%>

- **County with largest votes:**

    <img src="resources/Results_County_Largest.png" height=35% width=35% align="left">

    <img src="resources/Results_County_Breakdown_Code.png" height=60% width=60%>

- **Breakdown of votes and percentage of total votes for each candidate:**

    <img src="resources/Results_Candidate_Breakdown.png" height=35% width=35% align="left">

    <img src="resources/Results_Candidate_Breakdown_Code.png" height=60% width=60%>

- **Candidate winner:**

    <img src="resources/Results_Candidate_Winner.png" height=32% width=32% align="left">

    <img src="resources/Results_Candidate_Winner_Code.png" height=60% width=60%>
    
## Summary
As exampled below, this script allows an analysis of election outcomes and provides easy-to-read results in a text file.

<img src="resources/Summary_Results.png" height=35% width=35%>

Ultimately, this script can be used for any election with a few modifications.

### Potential Script Modifications
-  If we wanted to add ballot measures, we would modify the script to include both a list and dictionary of ballot measures and their votes. The code would be similar to that of the county and candidate breakdown codes above and would be placed in the same area in the script.
- If we wanted to show the vote count and percentage every candidate received in each county, we could add the key "candidate name" to each county's dictionary.