## Group Project: Comparison of changes by state in numbers of background checks in the years following presidential elections.

## Purpose:
Determine whether federal election victories by Democrats (on the state or national level) correlate to an increase in background checks for firearms in the following year, and whether trends are more significant in solidly "red", "blue", or in "swing" states.

### Contributors:
* Wynn Bigham
* Allan Hunt
* Alex Mogren
* Vince Dinolfo

### Contents:
#### Datasets folder:
* Election results by state for 2000 to 2016, for Presidential, House, and Senate.
* Background checks per year by state - full year data for 2000-2019 and partial data for 2000 and 2020.
#### Cleanup folder:
* For elections, isolated year, state, and Democratic vs Republican votes, and combined each type of election (Presidential, House, Senate) into its own CSV and calculated percent change between elections.
* Classified states as "Red", "Blue", or "Swing" based on the number of Presidential victories for Democrats for the 5 elections 2000 to 2016.
* For background checks, added up monthly data to produce yearly totals for each state.
#### Jupyter notebook:
* Combined background check data with presidential election data into a single Pandas dataframe.
* Created derived dataframes for the "red", "blue", and "swing" states.
* Used matplotlib and scipy.stats to construct regressions and graphs for each set of states (all, "red", "blue", and "swing") for all 5 elections, and another set for the two elections won nationally by the Democratic candidate.
