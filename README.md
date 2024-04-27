# Analytics of public procurement announcements
This data analysis project intends to provide descriptive findings of public procurement notifications in Norway.
Selected findings have been used in a written report deliverable in the course TIØ4859 - Innovasjon for en bedre verden at NTNU - Norges teknisk-naturvitenskapelige universitet. 


### Data sets
The data sets retrieved contains notifications of public procurements.

Retrieved CSV-files from:
https://dfo.no/nokkeltall-og-statistikk/innkjop-i-offentlig-sektor/kunngjoringer-av-konkurranse-pa-doffin#anchorTOC_Last_ned_datasettene_for_de_ulike_%C3%A5rene%3A_8

CSV-files for the following years have been retrieved:
- 2022
- 2021
- 2020
- 2019
- 2018

### In repo pandas-analytics
Two Jupyter Notebook files exists in this repo. 

#### EDA.ipynb
EDA (Exploratory Data Analysis) contains analysis of descriptive data used in report on preparedness in public procurement.
Analysis conducted include:
- Counting of all entries containing the word "beredskap" in the title.
- Counting of all entries continaing the word "beredskap" and the word "innovasjon" in the title. 
- Extracting most common procurers among entries with the word "beredskap" in the title.
- Plotting most common procurers among entries with the word "beredskap" in the title.

#### wordfrequency.ipynb
Word frequency analysis, finding most common words in title among those data set entries that cointains the word "beredskap" in title.
Most common words and their frequency number is shown both in a list format, as well as graphically displayed by means of a word cloud. The word cloud has been used for presentation purposes.