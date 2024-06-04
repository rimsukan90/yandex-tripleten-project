## Data:

The *visits* table (server logs with data on website visits):

- *Uid* — user's unique identifier
- *Device* — user's device
- *Start Ts* — session start date and time
- *End Ts* — session end date and time
- *Source Id* — identifier of the ad source the user came from
- All dates in this table are in YYYY-MM-DD format.

The *orders* table (data on orders):

- *Uid* — unique identifier of the user making an order
- *Buy Ts* — order date and time
- *Revenue* — Y.Afisha's revenue from the order

The *costs* table (data on marketing expenses):

- *source_id* — ad source identifier
- *dt* — date
- *costs* — expenses on this ad source on this day

## Goal:

 To help optimize marketing expenses. 

## Libraries used:

pandas, numpy, math, matplotlib.pyplot, scipy.stats, seaborn
