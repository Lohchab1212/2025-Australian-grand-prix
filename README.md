# Reading the Race — F1 Tyre Strategy with Python

## Overview
This project is about going through the tyre strategy of Scuderia Ferrari HP F1 team during the 2025 Australian Grand Prix.

## RACE - 2025 Australian Grand Prix
Why this Grand Prix? Since this Grand prix was a rainy one and a true F1 enthusiast 
knows how strategic a semi wet race is because getting right window fro the inters(Tyre Compound). It all comes down to the timings of the pit stop how well you time the pit stop with the rain starting
as well as when the track becomes dry you don't want to be one with the inters. This race focuses on the tyre strategy of the Ferrari F1 team.
## Key Findings 
This race was pretty much a dry race till lap 30 then as the rain started getting heavier the drivers need to change the tyre as soon as possible otherwise they lose the track position and time or worse 
they could crash.
1. Hamilton pitted a lap earlier than Charles Leclerc. HAM pitted on lap 33 and LEC pitted on lap 34
2. Hamilton was faster on Hard tyres possibly due to fresher rubber and better setup for dry conditions.
3. Leclerc had the edge on inters lapping faster than Hamilton and overall had better wet race pace.
## Visualisations
<img width="1400" height="600" alt="tyre_strategy" src="https://github.com/user-attachments/assets/54252802-e492-4b89-a19a-27ac72fe1155" />
This plot showed the overall tyre compund usage by both the the drivers during the Australian Grand Prix
<img width="1400" height="700" alt="ham_vs_lec_strategy" src="https://github.com/user-attachments/assets/2e8e5b70-0f18-4ea4-a863-65e7e8d76cc9" />
Here is the lap vs lap tyre and race pace for the drivers which makes it easy to read the plot proving the earlier findings.
## Tools Used
 FastF1 -  for the race data 
 matplotlib - for all the plotting 
 seaborn - for the visualisation
### Data Source
 FASTF1 - Here you can get all the race data from F1
### Next Step
 Next step will be predicting championship using the data of first 12 round of the Calender before the summer break.
