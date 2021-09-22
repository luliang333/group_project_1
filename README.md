# group_project_1

### Hypothesis

Is there a relationship between where you live and rate of new cancer cases?

To do:

* Join CSV and API data
* Apply .dropna() and make sure it's clean (Nevada has no lat data, keep or ignore?)
* Run T-Test, ANOVA, and Chi-Square Test to check if we have a viable hypothesis
* Based on test results, write our alternate and null hypothesis
* Build graphs to support our findings

The areas we will look at are:

1. Time zone (lng) vs. cancer rate
	- Pacific Time (PT), Mountain (MT), Central (CT), Eastern (ET)

2. Location (lat) vs. cancer rate
	- Lower 48 states

3. Poverty rate vs. cancer rate in each county in California

The sources we will use are:

* Lat and Lng from Google Maps API
* 2018 Poverty and Income from US Census data API
* Cancer rate from CDC CSV
