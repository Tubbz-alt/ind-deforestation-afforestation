# Deforestation algorithm 
## Summary
<!-- Add a one or two sentence to describe this indicator -->
This algorithm is intended to monitor the status of forests, based on sentinel 2 time series. The algorithm output is a classified layer that identifies the following classes: 
-(1) recently deforested (bare soil)
-(2) deforested with signs of regrowth (herbaceous, non crop cover)
-(3) deforested and signs of land use change (replacement by grasslands or crops)
-(4) afforestation (shrubs and small trees detected in at least xx% of the area)
-(5) not deforested 
## Details
<!-- Add a more detailed description about this indicator -->
Accuracy must at least equal 90%. The class assigned to each pixel must remain unchanged for at least 2/3 of the latest dates in order to reduce errors. Resolution of the output layer must be 20m or better. 

## Status
<!-- Choose one of the following Draft | Proposed | In Review | Production -->
- Draft: work in progress
- Proposed: waiting for review 
- In Review: under review
- Production: in production

## Revision History
v0.1 - initial draft

# Contributors
Your name

