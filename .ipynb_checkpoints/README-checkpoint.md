# US Electricity

## Dataset
### Data Engineering
Pull for -

**Net generation** for California (region), hourly - UTC time (in megawatthours)

https://www.eia.gov/opendata/qb.php?category=3390021

Trigger using lamda job to :-
1. fetch data every 6 hour for latest 6 records
2. store the data in s3 folder


