# Survey Analysis

This [python notebook](./analysis.ipynb) was used to run an analysis of the results of the [data survey](survey_results.csv), run as T3.1 of the H2020 research project: 945307 - eMOTIONAL Cities.

This notebook uses the [OpenCage geocoder](https://opencagedata.com/), to geocode the results of the survey. In order to enable the map, you need to create a configuration file with the OpenCage key. 

1. Signup for a free key [here](https://opencagedata.com/users/sign_up).
2. Create a configuration file at the root of this folder, called `config.py`. The contents of this file should be `OpenCage = {'key': '[PUT YOUR KEY HERE]'}`.

