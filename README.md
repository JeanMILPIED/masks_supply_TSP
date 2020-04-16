# masks_supply_TSP

# Optimum delivery of masks in Paris
## TSP like problem
## Question: how should be structured the mask supply to have a minimum number of storage places and a minimum distance between storage and deliveries in Paris hospitals and care center

Actions:
- list of all hopitals and care center in Paris city
    - we can then look at expanding to all Ile de France
- consolidation of weekly needs of each hospital with hypothesis (that can change)
- it is very hard to find the number of workersper places selected
- it is then very hard to define the need
- list of constraints:
  - match the need everyweek (cneed cannot be defined)
  - minimum masks transport in Paris city from storage to needed place: minimum "loop distance" per cluster
-   minimum storage places
-  existing places are storage places
