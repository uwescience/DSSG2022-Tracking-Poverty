---
layout: page
title: Method 2
---


In addition, we incorporated longitudinal household changes to improve imputed addresses. By comparing the distribution of households by size using census and naive co-residences from WMLAD in April 2010, we decided to focus on revising one-person residences that we overestimated. 

We identified three scenarios that led to the overestimation of one-person residences.

Lack of interactions 
- Some household members, especially children, interact with government agencies less frequently than adults, which leads to fewer recorded addresses for imputation. For example, only when a child registers to vote or receives a driver’s license, would an address be recorded in the administrative data. If a child, defined as those below the age of 18, occupies the same address with others, we adjust the one-child residences in the same address as the co-residence the child belongs to.   

*picture*

Imputation error
- Frequent movements into and out of the same place are likely to represent an imputation error. If we observe one person lives alone and co-appears with others alternately in the same address, we adjust the one-person residences as the nearest co-residence that the person belongs to. 

*picture*

Move in and out 
- One-person residences could also occur in the transition period when a multi-person residence moves out at the same time to a new place but their addresses are not updated accordingly. If we observe distinct co-residence members prior and subsequent to a one-person residence in a given place and the prior co-residence appears again in the future, we adjust the one-person residence as the subsequent co-residence. 

*picture*

After revising one-person residences that fall under any of the scenarios, we leveraged recorded addresses to remove duplicated residents to make sure that each person could only occur once in a given month.  
