# data
Processed data files for analysis. All data is publicly available and free.

### Navigating the repo:

- Data related to the 2020 November elections should go in the top-level `2020_november` directory
- Generally, folder names should indicate the delimiter of the data contained therein.
  - As of 1pm, Nov 11, `2020_november` contains cleaned results data delimited by county
  - Cleaned results data delimited by **precinct** will be uploaded soon!
- Data has also been collected on participation rates from the 3 most recent state-wide run-off elections
  - each sub-folder in the `recent_runoffs` directory contains data for the initial election AND the runoff
  - the runoffs data is currently **precinct-delimited**


### Directory Structure:

```
demographics
elections
  |- 2020_november
    |- county_delimited_results
      |- cleaned
        |- [sub-folders for each categories of race containing election result CSVs]
      |- raw
        |- data.txt

    |- precinct_delimited_results   # (coming soon)

  |- recent_runoffs
    |- 2016_may (General Primary)
    |- 2018_may (General Primary)
    |- 2018_november (General Election)
voters
```

#### Sources

- Election results data: https://results.enr.clarityelections.com/GA/105369/web.264614
- Voter participation data: https://sos.ga.gov/index.php/Elections/voter_registration_statistics
- Precincts shape files: https://openprecincts.org/ga/
- Demographics: US Census Bureau
