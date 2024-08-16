Xpert Learning Assistant:
* Look for the loc. the syntax for the field that contains a specific string of words to filter only the Summer Olympics
* Look at how to force a date format and skip the error
    - Function definition to identify entries with year only
    - Function to convert to date format string date format: dd month yyyy and month yyyy
* Drop multiple columns at once
* Extract the days after subtracting dates to calculate ages .dt.days
* pd.to_numeric to skip the error and make it NaN
* Filter a DataFrame created from a 3 column groupby using the slice syntax
* Syntax to find values common to a set of years
* How to plot side-by-side two bar plots and have nice gender parity charts per sport
* How to make years in float format become categories for plotting / range(len(x_values))
* How to adjust the FacetGrid x axis to make it wider
* How to create a box plot with separate boxes per year (the plot was reading year as a number instead of a category), for weight and height through a for loop / for i, year in enumerate(x_labels)
* How to add a column to a df while running a for loop to mark with '1' the rows that are the outliers of height and weight
    - How to count inside this same for loop the outlier of height and weight per year and place them inside a new data frame to see the possible connection between gender parity trend and the number of height and weight outliers
* How to make the titles of plots have a bold font

Office hours:
* Matt helped me with the Faceted plot for a side-by-side comparison of the number of athletes in each sport throughout the years.

* He also guided me on how to groupby the categories with low percentages into an 'Other' category in a df to improve the readability of a pie chart.

Limitations:
The born column of the athletes_bio_csv had complete date format entries, month-year entries, year entries, typos, and empty values. We decided to use only complete date format entries and month-year entries, knowing that the forced date format will automatically make the month-year entries the first day of the month. We only discarded the year entries, typos, and empty values.

Trying to narrow down the sports common to all Olympics, we found out that although the Olympics started in 1896, women started to participate in figure skating in 1920. From the 1924 to 1932 Olympics, women's participation varied to other sports like Diving, Fencing, Swimming, and athletics. However, it was not until 1936 that participation increased in different sports and was steady in Athletics, Swimming, and Artistic Gymnastics. This is why the weight and height analysis will be done on these three sports for both genders.





