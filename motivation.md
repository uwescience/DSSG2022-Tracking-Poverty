---
layout: page
title: Motivation
---

**Research Questions**

Poverty is a household-level construct that examines resources shared among multiple individuals. There are numerous factors that may define a household, like age, aging, culture, class, immigration, and education. A household connects multiple intersecting identities and holds the complexities of our society. Households tell stories that cannot be seen in individual-level data. Yet, as there is no one social definition for a household.

We used information stored in the Washington Merged Longitudinal Administrative Dataset (WMLAD) to create working definitions of households, based on addresses and last names. Specifically, we’ll be answering the following questions: 

- What are some of the different definitions for households in Washington state? 
- How do we form different types of households using longitudinal administrative data from multiple state agencies? 
- How do we work with different datasets to create household definitions that can encompass society as holistically and accurately as possible? 


**Background**

In 2014, Seattle passed a $15 minimum wage ordinance hoping to reduce income inequality. This ordinance was implemented incrementally over several years by employers. Researchers interested in the relationship between poverty, income, and employment saw this as an opportunity to measure the efficacy of the minimum wage as an anti-poverty policy intervention. 

Recognizing the potential of administrative data to answer these and other questions, the Washington Merged Longitudinal Administrative Dataset (WMLAD) was created by compiling individual information from six agencies that held information about demographics, income, health records, addresses, and more. Because administrative data is not built for research, many of the previous WMLAD studies focused on questions that helped restructure the datasets to allow more questions to be asked in the future, such as imputing monthly residential locations of adults. Others focused on the minimum wage’s impact on poor workers, parental employment, and geography and equity. 

This study focuses on using WMLAD to construct households in order to answer questions about household poverty. The way a household is defined has changed dramatically over the years. In the past, households have been synonymous with family units. The census, on the other hand, defines a household as the following: “A household includes all the persons who occupy a housing unit as their usual place of residence.” WMLAD contains information from agencies that each have their own definitions of households. For example, SNAP, a basic foods program within DSHS, defines one Assistance Unit (AU) as people that buy food together, prepare meals together, or both. Additionally, other researchers that have used administrative data to consider households have used parameters such as age, number of people in households, addresses, and rules to group household types. Our end goal is to construct households that reflect the nuances of society. 


**Stakeholders**

Engagement with stakeholders was a critical part of the process of working with the WMLAD data to form the different definition of households. The team communicated with a variety of stakeholders including two members from the Department of Social and Health Services (DSHS), previous Ph.D. students who had worked with WMLAD, a policy analyst and organizer for the $15 minimum wage in 2014, and Jennie Romich, Director of the West Coast Poverty Center. These conversations informed our understanding of WMLAD, contextualized our work, and the need to measure poverty at a household level.


We have identified three use cases:
- Create a relational database and documentation to inform future WMLAD researchers
- Provide approaches for constructing households to derive and improve household and family identifiers
- Analyze results using WMLAD data to inform future researchers


**Ethical Considerations**

At every step of this project, we have considered the ethical questions that arise in working with a highly-sensitive dataset involving real people and social constructs.

Privacy
- The WMLAD data contains information aggregated across multiple sources about the demographics, residential addresses, employment, and income – among other things – of over 10 million people in Washington state. Although we work with de-identified data, the magnitude and sensitivity of the information it contains requires we take extreme care to keep it private. In addition to working through a secure data enclave, we made sure to only share the minimum amount of information necessary to tell a story, and we focused our analysis on information about populations, not people.

Consent and Accountability
- Our work makes use of data that was collected for administrative purposes, not for research, and therefore the data subjects did not consent to participation, nor could we feasibly attempt to obtain their consent. Therefore, we must balance the public good made possible by our research (and by the future research of others who use our results) with the risks it may pose to the people in our data. It is in part for this reason that we do not use data on refugee status or encounters with law enforcement. Unfortunately, in keeping the data safe and secure, we cannot produce reproducible examples for independent researchers to corroborate our results, so we emphasize accountability internally and share as much about our methods as possible without compromising data privacy.

Embedding Social Constructs in Technology and Data
- We acknowledge that there is no single, objective definition of a household or a family, nor should there be. We created multiple definitions to be used for different research purposes, but still we inevitably had to make decisions about what types of household formations to include. In grouping the population in our data into households, we must address the reality that our definitions are easier to operationalize for traditional, Western family types. WMLAD is only able to capture people who interact with the administrative systems that provide its data, and we are limited by the information contained in the data, which is by no means “truth.” At every step, we interpret data with caution, questioning its meaning and accuracy, considering which populations it leaves out, and including non-traditional and non-Western family types whenever possible.

