# Tornadoes in Canada from 1980 to 2009

[Website]('https://www.linuxnorth.org/pandas/')


## Source

####  [Canada Open Data](https://open.canada.ca/data/en/dataset/fd3355a7-ae34-4df7-b477-07306182db69) - [License](http://open.canada.ca/en/open-government-licence-canada)

## Goals

* To look at the Government of Canada Dataset on Tornadoes from 1980 and 2009 and their impact on the Canadian population.
* To attempt to better understand where tornadoes are more likely and when.
* To attempt to understand the financial impact on Canadians of tornadoes.

## Limitations of Dataset

* The only data available from the Government of Canada covers the 1980 to 2009 period.
* There is missing data on the total size of tornadoes.  No distinction is made on what F category a tornado has. A F1 tornado is treated the same as a F4 tornado for example.
* This only captures tornadoes that were recorded.  It would not take into account tornadoes that hit non populated areas.  Therefore I always qualify findings as 'tornadoes in populated communities'. No data can really be discerned on the amount of activity country wide.
* As this is a learning exercise only, no attempt is being made to add extra data from other sources or the periods of 2010-2019.  The goal is to see what this government provided dataset actually tells us.


## Assumptions

* Human/Animal Death/Injuries often show -999.  This can either mean no deaths or unsure.  I will assume 0 deaths
* Damage to housing is an ambiguous column.  Assumption made that 000 is 000(000) based on the amount of deaths and injuries
* House Damage data often shows -999.  This number either signifies no significant damage or unknown.  I will assume 0 damage.

## Interesting work happening today to study tornado activity in Canada

The data provided by the OpenData portal is seriously lacking.  It appears a team of researchers have taken on the task to better understand tornado activity in Canada.  

[The following link from the Weather Network provides a brief synopsis of the work happening.](https://www.theweathernetwork.com/ca/news/article/northern-tornadoes-project-aims-to-catch-every-twister-in-canada-in-2019-environment-canada-western-university
)

