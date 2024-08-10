Xpert Learning Assistant:
* Look for the loc. syntax for field containig a specic string of words to filter only summer olympics
* Look how to force a date format and skip the error
    - Fuction definition to identify entries with year only
    - Function to vonvert to date format string date format dd month yyyy and month yyyy
* Drop multiple columns at once
* Extract the days after substracting dates to calculate ages .dt.days

Limitations:
The born column of the athletes_bio_csv had complete date format entries, month - year entries, year entries, typos and empty values. We decided to use entries only with complete date format entries and month - year entries knowing that the forced date format will make the month - year entries be automatically the 1st. day of the month. We only discarded the year entries, typos and empty values.

