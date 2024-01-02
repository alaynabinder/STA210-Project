# Data

This data is the Washington Post Fatal Force Database. There are two datasets, one that containts information about the death record of the victims and another than includes information about the agency related to each incident. The data spans from 2015 to present day and is updated daily by researches at the Post. Every record must have at least two sources and be approved by an editor before being published. 

## fatal-police-shootings-data

| Variable                   | Description                                 |
|:---------------------------|:--------------------------------------------|
| id                         | a unique identifier for each victim         |
| date                       | the date that the shooting occurred         |
| threat_type                | Actions the victim took leading up to the shooting |
| flee_status                | whether or not the victim tried to flee     |
| armed_with                 | if the victim was armed and if so with what |
| city                       | the city that the shooting occurred in      |
| county                     | the county that the shooting occurred in    |
| state                      | the state that the shooting occurred in     |
| latitude                   | The latitude location of the shooting       |
| longitude                  | the longitude location of the shooting      |
| location_precision         | the precision level of location data        |
| name                       | name of victim                              |
| age                        | age of victim                               |
| gender                     | gender of victim                            |
| race                       | race of victim                              |
| race_source                | sourcing methodology for race of victim     |
| was_mental_illness_related | whether the victim had a history of mental illness or was experiencing a crisis at the time of the incident |
| body_camera                | whether the police had a body camera or not |
| agency_ids                 | list of agency ids associated with the death record |
                               

## fatal-police-shootings-agencies

| Variable        | Description                                |
|:----------------|:-------------------------------------------|
| id              | department database id                     |
| name            | department name                            |
| type            | department type ie. sheriff                |
| state           | state the agency is located in             |
| oricodes        | department ORI codes (federal identifiers) |
| total_shootings | number of police shootings that the agency has been involved in |
