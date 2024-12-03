# U.S. Elections (official election night results)

This is a companion repository to [us-elex-2024-bx](https://github.com/cmgsalazar/us-elex-2024-bx), which mapped *unofficial* election night results in the Bronx, at election district level. 

For a more thorough insight on how Bronxites vote, I looked at data from the 2016 and 2020 elections. While this repository filters data for the presidential race and specifically in the Bronx, the lines of code may be adjusted to cater to other positions and coverage areas. 

Resulting analysis will be used for a reporting assignment for the [Mott Haven Herald](https://motthavenherald.com/) and [Hunts Point Express](https://huntspointexpress.com/). 

![image](https://cmgsalazar.github.io/newmarkj/how-bronx-voted-elections/images/bx-elex.gif)

## Data source

* New York City Board of Elections — [Election Results Summary](https://vote.nyc/page/election-results-summary)

## Content 

`analysis.ipnyb` is the main Python Jupyter notebook used for filtering datasets and processing vote counts for visualization.

`data` holds raw datasets, downloaded from the NYC BOE website.

`csv` holds the processed datasets for visualization. 

## Visualization

JSON files were downloaded via [NYC Planning](https://www.nyc.gov/site/planning/data-maps/open-data/districts-download-metadata.page) and [toddwschneider](https://github.com/toddwschneider/nyc-presidential-election-map), then processed through [Mapshaper](https://mapshaper.org/) and Adobe Illustrator and Photoshop.

See [repository](https://github.com/cmgsalazar/cmgsalazar.github.io/tree/main/newmarkj/how-bronx-voted-elections) for image files and prototype page. 