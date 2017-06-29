## About
This repo is the [app_frame/jekyll/pym version](https://github.com/energyapps/app_frame) of something that was built in 2013. The original repo is found [here](https://github.com/energyapps/egallon).

## Background information
Read the blogs if you're curious about how this came into being. The cms map itself is located [here](https://energy.gov/maps/egallon).

Read about it [here](https://energy.gov/eere/electricvehicles/saving-fuel-and-vehicle-costs) and the methodology can be found [here](https://energy.gov/downloads/egallon-methodology).

More articles:
- https://energy.gov/articles/egallon-how-much-cheaper-it-drive-electricity
- https://energy.gov/articles/egallon-what-it-and-why-it-s-important
- https://energy.gov/articles/ev-sales-skyrocketing-egallon-holds-steady
- https://energy.gov/articles/egallon-and-electric-vehicle-sales-big-picture

## Data
The most important part of this is knowing where the data is from, and how it is collated. All of the data is from EIA. The electricity data is updated on a monthly basis and can be found in tabular form [here](https://www.eia.gov/electricity/monthly/epm_table_grapher.php?t=epmt_5_06_a). The gasoline is updated on a weekly basis but is not present for every state, therefore some states are grouped by region. It can be found [here](https://www.eia.gov/electricity/monthly/epm_table_grapher.php?t=epmt_5_06_a). Both sets of data are gathered from the EIA API using a script on energy.gov's servers ([electricity price](https://www.eia.gov/opendata/qb.php?category=1012), [gas price](https://www.eia.gov/opendata/qb.php?category=240691)). This script runs weekly and the resulting data can be found at https://energy.gov/api/egallon/current/combined.json.


## CSS
The css stuff is heavily modified but one essential part is based on [this countdown clock](https://codepen.io/ademilter/pen/czIGo). 
