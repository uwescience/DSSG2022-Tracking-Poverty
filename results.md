---
layout: page
title: Results
---

**Point-in-Time**

Seattle Map

<img src="{{ site.url }}{{ site.baseurl }}/assets/img/seattle_hh_maps.png">


**Longitudinal**

After implementing the modification algorithm and removing duplicates, the proportion of one-person residences decreased from 38% to 31%, which was closer to the census data. 

<img src="{{ site.url }}{{ site.baseurl }}/assets/img/long_results.png">

**Deliverables**

We produced the following deliverables as a part of this project:
- PostgreSQL database with clear schema
- Longitudinal household file modifying certain anomalous cases of one-person households for April 2010
- Point-in-time (April 2010) household file on the individual level with their household ID for each definition (naive, last name deterministic, and last name probabilistic)
- Point-in-time household files, one for each definition, with each household ID and its characteristics
- Summary tables of the distribution of household sizes for each definition
- Summary maps
- Documentation of the code, workflow, concepts, and analysis

They will be used by future teams working to improve the household definitions and by future researchers working on using the existing definitions for their analyses.
