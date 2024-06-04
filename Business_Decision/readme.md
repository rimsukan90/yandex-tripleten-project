## Data:
Data used in the first part of the project

/datasets/hypotheses_us.csv

- *Hypotheses* — brief descriptions of the hypotheses
- *Reach* — user reach, on a scale of one to ten
- *Impact* — impact on users, on a scale of one to ten
- *Confidence* — confidence in the hypothesis, on a scale of one to ten
- *Effort* — the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the test.
Data used in the second part of the project

 /datasets/orders_us.csv

- *transactionId* — order identifier
- *visitorId* — identifier of the user who placed the order
- *date* — of the order
- *revenue* — from the order
- *group* — the A/B test group that the user belongs to
/datasets/visits_us.csv

- *date* — date
- *group* — A/B test group
- *visits* — the number of visits on the date specified in the A/B test group specified

## Goal:

Prioritize the hypotheses, launch an A/B test, and analyze the results

## Libraries used:

pandas, numpy, math, matplotlib.pyplot, scipy.stats, seaborn
