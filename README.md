# Least Driveable Pittsburgh Neighborhood
**Team Name**: Small Ideas
## Members

- Jake Kressley (jak483@pitt.edu)
- Vishal Suthakar (vis108@pitt.edu)

Our team is looking to find the neighborhood in Pittsburgh that is the "worst" to drive in. We will be looking at speed hump count, traffic count, and crash frequency. 

## Datasets Used

- [Number of Crashes (2021)](https://data.wprdc.org/dataset/allegheny-county-crash-data)

Contains data of every crash in Allegheny county from 2021 (Decided to only do 2021 instead of 2004-2021 because it took an unbearable amount of time to use). By pairing with Neighborhoods dataset(see below) we will match each crash to its respective neighborhood. More crashes means a neighborhood is worse to drive in.

- [Number of Speed Humps](https://data.wprdc.org/dataset/city-of-pittsburgh-speed-humps/resource/37b2ac41-ae8e-4de1-8405-157e05dc3640)

Contains counts of speed humps in each neighborhood in Pittsburgh, the more speed humps, the worse the neighborhood is.  

- [Traffic Count](https://data.wprdc.org/datastore/dump/6dfd4f8f-cbf5-4917-a5eb-fd07f4403167)

Contains daily count of cars that drive through each neighborhood. The more cars, the more traffic.

- [Pittsburgh Neighborhoods](https://data.wprdc.org/dataset/neighborhoods2)

Details the boundaries of each neighborhood so we are able to place the crashes within their respective neighborhoods. 
