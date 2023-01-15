

# Brain drain and economic growth: theory and evidence (2001)
- Theoretical paper but provides some interesting results
- Focuses on the impact of migration prospects on creation of human capital in small, open developing economy
- people invest in education to successfully migrate because of higher returns abroad
- Beneficial Brain Drain (BBD): Average level of human capital is higher in the economy with emigration opportunities than not

1. Determing the theoretical impact of migration on human capital for countries that are a source for immigrants

2. Countries that are a source for immigrants foster an environment in that source country that raises the average lvel of human capital in such country vs those who are not sources for migration

3. Although mostly theoretical, for empirical data the model uses cross-sectional data (a type of data collected by observing many subjects at the one point or period of time.) to measure migration rate, growth rate of gdp per capita, and education level as independent vairables.
	- to determine migration rate, 
	the model regresses: GDP per person of country measured / OECD countries mean - population - public expenditures in education % of gdp
		- The first relationship, implied by Eq. (3), establishes a positive link between migration opportunities and the proportion of young individuals who decide to invest in education. (282)
		- estimated in logs by OLS
	- to determine education level, the model regresses: - migration rate, migration rate multiplied by  adummy variable that is 1 if GDP/person is less than 15% of the average GDP/person in G7 countries, and positive on public expenditures in education % of gdp
		- The second relationship that can be estimated is derived from Eq. (5) and states that the growth rate is positively linked to the share of educated people and negatively affected by migration flows. (282)
		- estimated in logs by OLS
	- to determine growth rate in gdp per capita, the model regresses: - migration rate, education level, and workers remittances % of GDP (money sent back from another country)
		- estimated in levels

The countries in sample are: Algeria, Bangladesh, Brazil, China, Colombia, Cuba, Cyprus, Dominican Republic, Ecuador, Salvador, Fiii, Ghana, Guatemala, Guyana, Haiti, Honduras, Hong Kong, India, Iraq, Iran, Jamaica, Kenya, Lebanon, Malaysia, Mexico, Morocco, Nigeria, Pakistan, Philippines, South Africa, South Korea, Sri Lanka, Surinam, Thailand, Trinidad and Tobago, Tunisia, Turkey.

4. The Migration rate is positive and significant in correlating migrations and wage differentials. The R-squared for determining education level is high and the coefficient for the migration rate when multiplied by a dummy variable is positive and highly significant. Per the article, this means that an incetive effect of migration prospects cant be dismissed on empirical grounds. Referred to as poorly estimated, the OLS regression for growth rate for gdp per capita displayed a positive link between human capital improvements and growth in gdp per capita. Poeple may migrate more when investments in education is higher in their home country.

5. There are not any particular unanswered questions offered by the paper for further review. That being said, there is the question of the usage of more empirical data as this paper was published in 2001. We could, in theory, use the empirical model with updated data to see if the theorical model holds and/or improve upon the empirical model.

6. We can use this paper as a motivation to continue the work on brain drain and its impact on source and destination countries while also taking inspiration from the theorhetical models and reasonings provided here.

# Brain Drain or Brain Bank? The Impact of Skilled Emigration on Poor-Country Innovation (2011)
1. Estabishing an understanding of whether emigration harm domestic knowledge or instead, help.
    - "Our empirical focus is on the knowledge access of frontier innovators in a poor country." (3)
2. Emigration from a particular location has a positive effect on the location with regards to the amount of patents being recorded. This is because of the emigrators access to the frontiers of technology and sharing back with their compatriots at home.
    - "However, to the extent that networks for knowledge access operate similarly for frontier- and implementation-based innovation, the findings on the drivers of knowledge flows at the frontier should provide a valuable clue to the relative importance of local versus diaspora knowledge networks, and thus the likely impact of skilled emigration on poor-country knowledge access and innovation." (3)
3. Uses the Knowledge Flow Production Function to help model the probability of receiving knowledge from any other innovator.
    - focuses on colocation in the domestic economy
    - shares a diaspora connection
    - or are unconnected by loation or nationality
    - _we could regress a potential model based on the city, province data provided by the patent office of the innovator, maybe we could regress the city/states population delta with a 1yr lag with the amount of innovators in the following year_
    - how to isolate causal impacts of location and diaspora connections:
        - "The empirical challenge is to identify the co-location and diaspora effects in the KFPF. To accomplish this, we construct a novel sample from patent data linked with Indian last name data and then build on a widely-used method that employs patent citations as a proxy for knowledge flows between inventors and “matched citations” to control for the underlying distribution of inventive activity across geographic and ethnic space."
        - "This allows us to isolate the causal impacts of location and diaspora connections on the probability of a knowledge flow."
        - pretty much, we're minimizing the ability to count a potential knowledge share based on sharing same city alone
    - Empirical Strategy:
        - Patent citations are possible noisy indicators of knowledge flows
        - matches technology class and timing of each of the cited patents as closely as possible. Would bring the same geogrpahic distribution (10)
        - Use USPTO data by 2004 during the 1981-2000 period
        - patent citaions as a proxy for knowledge flows
    - Dependent Variable is citation which is a dummy variable assigned a value of 1 if actual citation or 0 if control.
    -   co-location is a dummy variable assigned to 1 if one of the inventors on the cited patent is located in india
    - diaspora is assigned to 1 if one of the inventors has an indian last name and none of the inventors are located in India
    - the model: Citation = 1|SameCountry, Diaspora) = a0 + a1SameCountry + a2Diaspora + e
    
4. The report finds (with logistic OLS regression) a large and statisically signifcant co-location effect and a signicantly smaller but still significant diaspora effect.
    -  the much larger colocation premium (0.806 v. 0.135 estimate) implies that the total access of India residing inventors to knowledge is harmed by the absence of fellow Indian inventors. Furthermore, the very large colocation premium confirms the importance of localized knowledge flows.
    - There exists evidence of a premium for knowledge flows when it comes to co-locations.
    - There also exists evidence of a premium for knowledge flows when it comes to diasporas.
    - Bottom line, there exists a knowledge flow but the paper finds that emigration is still harmful to the domestic economy.
5. Again, with the first paper, we could use much more updated data--this paper was written in 2008. Is this applicable to more countries where patent data is available on the same scale as the USPTO and can be applied to more than just India?
6. This paper provides significant support in expanding the search to more than just India and the USPTO but including the [top open patent offices](https://www.wipo.int/en/ipfactsandfigures/patents) and the [top countries with highest net negative migration](https://data.worldbank.org/indicator/SM.POP.NETM) might be interesting in the review. Following the diaspora and home country/state rule; this can definitely be useful in expanding the search.

# Brain Drains and Brain Gains: Causes, Consequences, Policy (2008)
1. Focuses on lifetime earnings and one's desire to pursue a personal research program in a location other than their current one.
    - Per the paper: "Originality/value – Provides insights on why, in a world of intensifying competition for scarce knowledge workers, countries can ill afford negative net migration of highly-skilled workers."
2. As this is a conceptual paper and more of a discussion piece, there's no particular thesis or stance this paper takes. Only wide
3. This paper attempts to answer the following questions through observations of other papers, all page 939:
    -  "...why do some knowledge workers of this kind emigrate from their home country while others stay at home? In common parlance, why do some people join the “brain drain” while others do not?"
    - "...should countries worry when they experience 'brain drains'?"
    - "...could government policy – in particular R&D policy – make a difference to the migration flows?"
4.To answer each question sequentially:
    1. Answers to question 1:
        - "Standard economic models (Sjaastad, 1962; Todaro, 1969) emphasise expected income differentials as the main driver of migration." (940)
        - "Researchers and scientists may attract income from a number of other sources: returns on financial assets, including equity – in companies for which they work and for which they do not; returns on physical assets, including residential property; and returns on intellectual property, including patents." (942)
    2. Answers to question 2:
        - "In general, the loss of such workers will be to the detriment of the economy of a country so long as their marginal social product is positive." (945)
    3. Answers to Question 3:
        - "...implies that national innovation policy can have an important influence on the migration decisions of RSE (researchers, scientists and engineers) workers." (946)
        - " In response to an increase in total government R&D spending, real and nominal private R&D spending are most likely to rise (ceteris paribus) when the labour supply elasticity is large." (947)
        - "All of this implies that only very early-career RSE workers prepared to adapt themselves to local needs would be likely to consider international migration to Germany for a long-term applied research career." (948)
5.
6. Another theoretical paper with little empirical evidence. Useful for the theory behind and references towards a motivation but not exactly for any pointers with regards to data or anything else. Pretty much, the paper is useful for as a basis for studying migration—not much else.
