## Data:

- *neighborhoods* table: data on city neighborhoods

- *name*: name of the neighborhood
- *neighborhood_id*: neighborhood code
- *cabs* table: data on taxis

- *cab_id*: vehicle code
- *vehicle_id*: the vehicle's technical ID
- *company_name*: the company that owns the vehicle
- *trips table*: data on rides

- *trip_id*: ride code
- *cab_id*: code of the vehicle operating the ride
- *start_ts*: date and time of the beginning of the ride (time rounded to the hour)
- *end_ts*: date and time of the end of the ride (time rounded to the hour)
- *duration_seconds*: ride duration in seconds
- *distance_miles*: ride distance in miles
- *pickup_location_id*: pickup neighborhood code
- *dropoff_location_id*: dropoff neighborhood code
- *weather_records* table: data on weather

- *record_id*: weather record code
- *ts*: record date and time (time rounded to the hour)
- *temperature*: temperature when the record was taken
- *description*: brief description of weather conditions, e.g. "light rain" or "scattered clouds"

## Goal:

Understand passenger preferences and the impact of external factors on rides.

## Libraries used:

pandas, numpy, math, matplotlib.pyplot, scipy.stats, seaborn
