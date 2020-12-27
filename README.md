## Comparison of changes by state in numbers of background checks in the years following presidential elections.
Group Project for University of Minnesota Data Analytics and Visualization (Week 7 of 24)

## Purpose:
Determine whether federal election victories by Democrats (on the state or national level) correlate to an increase in background checks for firearms in the following year, and whether trends are more significant in solidly "red", "blue", or in "swing" states.

### Contributors:
* Wynn Bigham
* Allan Hunt
* Alex Mogren
* Vince Dinolfo

### Contents:
#### [Presentation & Conclusions](https://github.com/arhunt/elections_vs_bkgr_checks/blob/master/presentation_conclusions.pdf)
* Project overview
* Graphs and regressions
* Results and limitations
#### _Datasets_ folder:
* Election results by state for 2000 to 2016, for Presidential, House, and Senate.
* Background checks per year by state - full year data for 2000-2019 and partial data for 2000 and 2020.
#### _Cleanup_ folder:
* For elections, isolated year, state, and Democratic vs Republican votes, and combined each type of election (Presidential, House, Senate) into its own CSV and calculated percent change from the previous election.
* Classified states as "Red", "Blue", or "Swing" based on the number of Presidential victories for Democrats for the 5 elections 2000 to 2016.
* For background checks, added up monthly data to produce yearly totals for each state and calculated percent change from the previous year.
#### Jupyter notebook `presidential_elections_and_background_checks.ipynb`:
* Combined background check data with presidential election data into a single Pandas dataframe.
* Created derived dataframes for the "red", "blue", and "swing" states.
* Used matplotlib and scipy.stats to construct regressions and graphs for each set of states (all, "red", "blue", and "swing") for all 5 elections, and another set for the two elections won nationally by the Democratic candidate.
