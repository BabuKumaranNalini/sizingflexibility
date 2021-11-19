OpenTUMFlex
=======

An open-source python-based flexibility model to quantify and price the flexibility of household devices.

[![DOI](https://zenodo.org/badge/212816117.svg)](https://zenodo.org/badge/latestdoi/212816117) [![Documentation Status](https://readthedocs.org/projects/opentumflex/badge/?version=latest)](https://opentumflex.readthedocs.io/en/latest/?badge=latest)


## Description

The increasing share of renewable energy requires alternative methods to provide power system ancillary services to ensure a stable operation of the electricity grids. Recent research has inclined their interests towards the aggregation of small-scale system flexibility potentials to accommodate grid variations. The advancements towards local flexibility markets (LFMs) allow prosumers participation in solving grid congestion problems. In order to allow prosumers to interact with the LFMs and submit their bids, a flexibility model is required. This research proposes an open-source flexibility estimation model that quantifies all possible flexibilities from the available prosumer devices and prices them.

#### Flexibility
Within this open-source model, flexibility is defined as the deviation of a device operation from its optimal schedule. Flexibility can be both negative and positive. Negative flexibility refers to the delay of grid feed-in or the consumption of unscheduled energy. Positive flexibility is the delay of grid energy consumption or the unscheduled grid feed-in.  


## Features
OpenTUMFlex...
* uses mixed-integer linear programming (MILP) to obtain cost-optimal operational schedules for household devices. 
* calculates the flexibility potential and flexibility prices based on price, weather, generation and load forecasts of household devices.
* supports the following devices: PV, battery storage systems (BSS), electric vehicles (EV), heat pumps (HP), combined heat and power (CHP) units.
* outputs flexibility offers for each household device in formats that can be used in flexibility markets (e.g. comax by Tennet or ALF by FfE e.V.)


## Installation



## Documentation
Find detailed documentation about OpenTUMFlex [here](https://opentumflex.readthedocs.io/).

