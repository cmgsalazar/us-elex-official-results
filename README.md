# U.S. Elections pre-2024

This repository contains 2016 and 2020 presidential election results data from the [New York City Board of Elections website](https://www.vote.nyc/page/election-results-summary). 

Resulting analysis will be used for a reporting assignment that looks into voting results in the Bronx, for the [Mott Haven Herald](https://motthavenherald.com/) and [Hunts Point Express](https://huntspointexpress.com/). 

**Related:** [2024 election results](https://github.com/cmgsalazar/us-elex-2024-bx)

![image](/viz/viz-map.png)

## Data sources

* [New York City Board of Elections website](https://www.vote.nyc/page/election-results-summary)

## Content and process

The `data` folder holds 2016 and 2020 vote counts in election districts in the Bronx. 

### notebooks

* `scraper.ipynb` used `BeautifulSoup` to scrape vote results per election district in the Bronx
* `clean-up.ipnyb` prepared and sanitized dataset for visualization

We created a new column that merges the assembly district and election district numbers, so we have a code consistent with geocode IDs. We added all Trump votes and Harris votes, then calculated the differential for choropleth mapping. 

We're using vote differential to visualize the data — instead of simply counting the number of votes — because **lands don't vote; people do**.

### data

* `bx-assembly_districs.csv` holds all links of Bronx assembly district votes breakdown
* `electoral_district_votes.csv` holds scraped unofficial election night results in each of the electoral districts in Bronx assembly districts
* `electoral_district_for_viz.csv` holds "prepared" data for viz

### `viz`

This folder holds our Illustrator and exported PNG file. 