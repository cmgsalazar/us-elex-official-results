# U.S. Elections (official election night results)

This is a companion repository to [us-elex-2024-bx](https://github.com/cmgsalazar/us-elex-2024-bx), which mapped *unofficial* election night results in the Bronx, at election district level. 

For a more thorough insight on how Bronxites vote, I looked at data from the 2016 and 2020 elections. While this repository filters data for the presidential race and specifically in the Bronx, the lines of code may be adjusted to cater to other positions and coverage areas. 

Resulting analysis will be used for a reporting assignment for the [Mott Haven Herald](https://motthavenherald.com/) and [Hunts Point Express](https://huntspointexpress.com/). 

![image](https://cmgsalazar.github.io/newmarkj/how-bronx-voted-elections/images/bx-elex.gif)

## Data source

* Vote counts per election district from [New York City Board of Elections](https://vote.nyc/page/election-results-summary)
* Election district coordinates from [NYC Planning](https://www.nyc.gov/site/planning/data-maps/open-data/districts-download-metadata.page) (H/T [toddwschneider](https://github.com/toddwschneider/nyc-presidential-election-map))

**Notes**:

* Boundaries of election districts vary due to redistricting.
* Shapefiles were processed into JSON through [Mapshaper](https://mapshaper.org/).

## Content 

```.
├── analysis.ipnyb  # main notebook used to filter datasets and process vote counts for visualization
├── csv             # holds processed datasets for visualization
├── data            # holds raw datasets, downloaded from the NYC BOE website
├── json            # holds shapefiles and JSON files for visualization
├── LICENSE
└── README.md
```

## Visualization

Maps were processed through Adobe Illustrator and Photoshop.

See [repository](https://github.com/cmgsalazar/cmgsalazar.github.io/tree/main/newmarkj/how-bronx-voted-elections) for image files and prototype page. 