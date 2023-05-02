# FL House of Representatives Scraper
This Python scraper is designed to extract photos and information of the current members of the Florida House of Representatives from the [Florida House of Representatives](https://myfloridahouse.gov/) website. It then saves the members' data into a CSV file named "House2023.csv" and their photos into a folder called "Photos".

## Purpose
The purpose of this scraper is to automate the process of gathering the photos and information of the members of the Florida House of Representatives.

## Functionality

For each member, the scraper extracts the representative's photo, name, party affiliation, district, and email. It then saves this information into a dictionary and appends it to a list of dictionaries. Finally, it writes the list of dictionaries into a CSV file named "House2023.csv" and saves each member's photo into a folder called "Photos" (the folder is to heavy for GitHub).

## Output
The output of this scraper is a CSV file named "House2023.csv" that contains the following information about each member of the Florida House of Representatives:

* RosterID
* VoterID
* Year
* OfficeCode
* Juris1num
* Filename

The scraper also saves each member's photo into a folder called "Photos". The filename of each photo is the member's RosterID followed by ".jpg".




