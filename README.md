# Analysis of Brookhaven Police Department Neighbors/Ring alerts data set — 01/2021 to 05/2022

This repository contains data, analytic code, and findings that support portions of the article, “[TKTKTKTK](https://www.google.com),” published Month Date, Year. Please read that article, which contains important context and details, before proceeding.

## Data

This analysis uses msg_extracts.csv spreadsheets.

The spreadsheets come from the following sources:

- Name of source:
  - `output/msg_extracts.csv`: Compiled data of Brookhaven Police Department Neighbors/Ring alerts

Each of the spreadsheets contain, among others, the following columns relevant to the analysis:

- The unique number of recipients
- Tallies over time
- Tallies of the 'title' column values containing “package” and “car”

## Methodology

The notebook [notebook/Final analyses of Brookhaven Neighbors alerts.ipynb] performs the following analyses:

##### Part 1: The unique number of recipients

- Found the total number of recipients and tallied the total alerts each received. 

##### Part 2: Tallies over time

- Found the total number of alerts sent during each month 

##### Part 3: Tallies of the 'title' column values containing “package” and “car”

- Analyzed the data to find the number of alerts that included either keyword in the title.

## Outputs

The notebooks output this spreadsheet which contains [Unique Recipient Count, Resampling by Month and Tally of Keywords](`output/unique_count_Love.csv`,`output/resampling_Love.csv`,`output/words_Love.csv`).

## Running the analysis yourself

You can run the analysis yourself. To do so, you'll need the following installed on your computer:

- Python 3
- The Python libraries specified in [`requirements.txt`](requirements.txt). You can install them by running `pip install -r requirements.txt`

## Licensing

All code in this repository is available under the [MIT License](https://opensource.org/licenses/MIT). The data file in the output/ directory is available under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

## Feedback / Questions?

Contact Randi Love at randirelove@gmail.com.
