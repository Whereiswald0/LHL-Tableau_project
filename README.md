# Final-Project-Tableau

## Project/Goals
### Tuberculosis has been endemic within the human population for at least 9000 years (according to the archeological record), while written evidence of the disease can be found going back 3000 years.

### According to the World Health Organization an estimated 1/3rd of all human beings are passive carriers of the TB bacteria right now. This brings with it a 10% lifetime risk of developing an active case of TB. This risk is further increased by other factors impacting health, such as poor nutrition and any disease effecting the immune system (autoimmune disorders, HIV). As a result of its very wide-spread, this disease is responsible for more cumulative deaths than any other pathogen and continues to claim the lives of 1.3 million people in 2021, only eclipsed by COVID 19.

### Currently, however, TB is entirely curable. Even the appearance of drug-resistant strains is only a moderate hurdle, since these strains are only resistant to the most common treatment options. Knowing this, I wanted to develop a set of visualizations investigating how closely a single economic lens (GDP) is tied to both incidence and mortality rates of an entirely curable disease.

## Process
### 1. Locate and append GDP data to TB data from WHO (see included Jupyter Notebook)
### 2. Examine WHO data to establish baseline numbers and trends globally, esp. regarding incidence and mortality by year, nation and region.
### 3. Determine if adding information about GDP increases predictive power of these models.

## Results - [link to data visualizations](https://public.tableau.com/views/TBCasesworldwideLHLproj/IncvMortbyyear?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
### While both incidence and mortality fell during the examined period (1990 - 2013), the distribution of both is unequal both BETWEEN regions and WITHIN them (this can be seen in the first and second tables)
### Maps visualizing the geographical distribution also suggest a link to nations with low GDPs.
### When asking Tableau to cluster this data both with and without including GDP as a contributing variable, we see several differences to the number and distribution of clusters. Again, this can be examined both between and within regions, which further supports the notion that GDP is a major contributing factor.
### Finally we can see a marked difference if the predictive power of GDP (R-Squared and p-Value) when examining the top 10% of nations when sorting by GDP vs. the bottom 10%, further indicating some nuance which may be uncovered by further analysis and the addition of other datasets with more fine-tuned economic metrics. 

## Challenges 
### Few challenges here, except for ensuring that the existing science of TB treatment and the comorbidities were adequately understood. The biggest issue was ensuring that economic data was properly joined across datasets given how different naming conventions we adopted, as both official names would change over the timeframe used by the datasets (USSR and 'post-Soviet' states (this is VERY complicated, see wiki re: Baltics), and english-language exonyms for many, many nations). There is further refining of the existing economic data to be done as well.

## Future Goals
### add additional economic indicators, include information about foreign aid and funding of UN and WHO projects.
