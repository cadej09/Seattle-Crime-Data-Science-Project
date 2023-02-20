#### Code name - WashCrime
## Project Title - Live in Safer Washington
### Authors -
Elizabeth McCrady _(elm53@uw.edu)_, Cade Jeong _(cadej09@uw.edu)_, Busung Chung _(bchung4@uw.edu)_, Sanika Gadam _(gadamsan@uw.edu)_
#### Affiliations - INFO-201 BD: Technical Foundations of Informatics - The Information School - University of Washington
#### Keywords - Washington, Crime, Safety
#### Date - AU22
## Abstract:
We are greatly concerned about the crime rates in Washington state, and specifically the neighborhood of the Seattle area. Because we are a group of students attending University of Washington - Seattle, who may live in those danger zones or have friends and families who do. To address this concern, we are seeking to discover patterns of crime in the interested areas and possibly influence the policymakers to take actions in reducing crimes, and increase the safety level for the citizens of Washington state.

## Introduction:
Crime rates in Washington have been on a steady increase since 2013 when the state ranked 30th for the states with the highest level of violent crime across the United States. It is an extremely pressing topic in the state of Washington and although laws have been implemented to reduce crime, it has still been on a steady increase in recent years. The types of crimes that occur in Washington include larceny, burglary, motor vehicle theft, and violent crime. The use of personal weapons, firearms and knives needs to be controlled by the government especially because juveniles have access to them and are contributing to the high crime rates in Washington. The number of violent crimes committed in Washington state are growing more than ever before and is it important for our society to bring light to this topic so that we can establish safety and security measures.

## The Problem Domain:
The heavy uprising in crime all over Washington has concerns over *human safety* and the protection of individuals. "Everyone has the right to the highest attainable standard of protection against natural and man-made hazards."(__Twigg__) Crime has been a constant uproar over the past years and the crime rates are still rising. As much as the government and many individuals want crime to go away, it is difficult. Safety is important when looking at different aspects in society. Culture is deeply rooted in human safety as well. Hate crimes that target certain race, gender, or cultural backgrounds are becoming a national issue. Statistics show that there had been a drastic increase of hate crimes during the pandemic and is still an ongoing issue. The government is trying their best to keep us safe as citizens of America, but there are still flaws in the system that make certain people vulnerable to crime. The right of safety can be interpreted through economic standards, where humans have the right to work in a safe environment without any worries of getting injured.  

The direct stakeholders include police officers, judges, probation officers, and parole officers. Lawyers, court personnel, and other individuals. The skills that are assumed, when looking at the direct stakeholders, we can observe that they require some direct involvement in the government system, where they contribute to keeping the nation stable through laws. I believe that the citizens of the nation are their first priority and the value that they hold the strongest.  Indirect stakeholders include elected officials, the media, groups who serve victims of crime, businesses, families, schools, and society in general.

I believe that through the interventions with data and technology, there would be a visible reduction of crime and will be beneficial to the people, however, this might lead to different types of crime that find a way under police surveillance. As technology advances by the day, criminals find more ways to go in and out of the system. The advancement of technology is a double sided knife, where it can help the government while it has the potential to portray harm to society.

We believe that businesses that have direct connection to the advanced technology will benefit the most through this innovation. On the other hand, unanticipated consequences such as, crime that involves more advanced technology might be used to harm people bringing the damage to the civilians.  

## Research Questions:
- How has the crime rate in Washington State changed over the last twenty years?
  - It is important to analyze trends in data in order to predict what potentially can happen in the future. If we pick up on patterns as to when crime rates were high or low, we can instill safety measures accordingly. If there is an outlier in the data, we can trace it back to an event that may have caused the shift in data.
- How much of the crime that happens in Washington is in or near Seattle?
  - Seattle is a big city and has a lot of crime. It is helpful to narrow down the area where crime occurs so that researchers can focus their attention to a smaller region and get more accurate data. Washington is a large state and if a lot of the crime is concentrated in one city, we can dive deeper into Seattle itself.
- Did the crime get worse or better during the years we suffered from COVID-19?
  - This is important to know because finding patterns can help us prevent something from happening in the future. We can anticipate crime rates going up or down when specific events occur and plan accordingly. This will save our community and economy from dealing with negative consequences more than once for the same issue.
- What kind of or type of crime is most common in Washington State?
  - In order to research what is efficient or not, we should know what kind of crime is most common. It will help us narrow down our focus on how to implement changes in policies to prevent future crimes.

## The Dataset:
We have so far found four datasets that are specifically about the crimes that happened in Washington State. Our first dataset _“CJDB90_20.csv”_ is a file that contains every possible information about crimes in Washington with its 228 variables. Going into more detail are _“nibrs_12_20.csv”_ and _“srs_94_19.csv”_. These two datasets happen to provide us a little more detailed information about the crimes in Washington than the first dataset due to having more compact variables and using different systems. Overall, we could use any of these datasets to answer our research questions in regards to finding patterns, change in crime rates for specific time periods, areas of crime, and so on. Our last dataset, _“SPD_Crime_Data_08_Present.csv”_ provides us in depth details for crimes reported by the SPD. This could help us find more detailed information about crimes in Seattle, which in the end will be able to answer our research question about nearby or in Seattle crimes. If in need, we will continue to update our list of datasets either by removing some that might not provide us much, or by adding more datasets to solidly answer our research questions.

| Data File| Purpose | Observations(rows) | Variables(columns) | Source |
| -------- | ------- |------------------- | ------------------ | ------ |
| CJDB90_20.csv | WA_Crime_Report | 1,271 | 228 | Data. Washington State Statistical Analysis Center. (n.d.). Retrieved October 31, 2022, from https://sac.ofm.wa.gov/data |
| nibrs_	12_20.csv | NIBRS_Report | 2,357 | 34 | Data. Washington State Statistical Analysis Center. (n.d.). Retrieved October 31, 2022, from https://sac.ofm.wa.gov/data |
| srs_94_19.csv | SRS_Report | 5,283 | 22 | Data. Washington State Statistical Analysis Center. (n.d.). Retrieved October 31, 2022, from https://sac.ofm.wa.gov/data |
| SPD_Crime_Data_08_Present.csv revised: spd_dataset.csv | SPD_Report | 1,011,283 | 17 | Spd. (2022, October 31). SPD crime data: 2008-present: City of seattle open data portal. Seattle Open Data. Retrieved October 31, 2022, from https://data.seattle.gov/Public-Safety/SPD-Crime-Data-2008-Present/tazs-3rd5 |

The first three datasets, CJDB, nibrs, and srs happened to come from the same source. These datasets were collected and organized by “Washington State Statistical Analysis Center” with their sources of data being listed on [this pdf](https://sac.ofm.wa.gov/sites/default/files/public/pdf/datades.pdf). Their work has the purpose of providing assistance in the successful coordination, implementation, and monitoring of public policy. And unfortunately, they do not list a specific date of when the dataset was created. SPD Crime Data dataset is collected by the SPD, updating on a daily basis using the nibrs system with only data that are UCR approved (Our dataset is up to date for 10-31-2022). It was created Feb 14, 2020 with the purpose of their work being similar to WA SAC.

Both of the sources had their data collection funded by the government. However, for WA SAC specifically, they received the help of Governor Booth Gardner, who authorized the Washington State Statistical Analysis Center in 1989 with Executive Order 89-03. And on top of that, they also receive help from JRSA (Justice Research and Statistics Association) and the Bureau of Justice Statistics. With such datasets being accessible to the public, there are hopes that these could be used by the policymakers to create laws that address the issues and benefitting the citizens with a safer living environment. Simultaneously however, there exist many threats as these datasets could be used by the wrong hands to create ways that could benefit the potential criminals, and make money for some companies.

Going back to [this pdf](https://sac.ofm.wa.gov/sites/default/files/public/pdf/datades.pdf), WA SAC not only list out their source of data, but they also go in depth to provide detailed information about each of their sources. For each of their sources, they talk about what kind of data is collected, what system they used to collect their data, what their sub-variables are about, and more to make sure how credible they are.

## Expected Implications:
If we answer our research questions some expected implications would be about the crime data we collect. Depending on how the crime rate has changed in 10-20 years would lead us to have an implication that we want to make a change. If the crime rate gets worse then us collecting this data will imply that we want to change and make the crime rate flip and go down. If the crime rate is going down then it's implied that we will see why it is going down and what we can continue to do. Another implication could come from our question of crime in Seattle and if we can narrow down specific areas. This can imply that we want to make those “dangerous” neighborhoods safer if they do have a high crime rate. If we can answer our question about how Washington State protects its citizens, it can help policymakers push for policies that would continue Washington helping its citizens.

## Limitations:
Most of the limitations we would have would come from a lack of data. For instance if we want to answer our question about which neighborhoods in Seattle have the most crime, we might not come across data that would aid in answering this question. We can address this by changing our question or by expanding the question into something we can address multiple cities in Washington with. Limitations could also come from gathering information from a bias source that may not have reliable data. We have to make sure that all data we collect and store is from an unbiased source and will help us answer our questions effectively.

## Findings:
- For our research question, **How has the crime rate in Washington State changed over the last twenty years?** What we have found for this is not exactly twenty years but rather the general trend in number of crime throughout the years recorded in our cjdb dataset. After doing some data wrangling, we found out that there was a slope of 5664 when comparing number of crimes in Washington state vs years. This means that each year, starting from the earliest date to the most recent date, there has been a 5664 crimes increase per year.
- For the research question, **How much of the crime that happens in Washington is in or near Seattle?** After organizing the dataset by counties, we were able to find that out of all the counties in Washington state, King county had the most crimes throughout the times of our cjdb dataset. Knowing that King county is the most common crime scene in Washington state, we took a look at the SPD dataset and was able to find out that there were 1,000,000+ crimes reported in Seattle alone.
- For our research question, **Did the crime get worse or better during the years we suffered from COVID-19?** We have found that there was a peak of crime in early 2020 when COVID was just arriving to the United States of America. After the pandemic began we can also see the variety in high and low crime days being drastically different rather than being closer together in numbers prior to 2020. We can tell that crime changed since COVID came to our state and there is a slight increase of crime after the intense peak during early 2020. Looking later at the data when our society is believing COVID is ending, we can see a decrease in crime around mid to late 2022.
- For our research question, **What kind of or type of crime is most common in Washington State?** After organizing the dataset by the categories/types of crimes in all of Washington state data, we have found that the **most** common type of crime in Washington state had been _Theft_ in which motor vehicle theft had been the most common. And the **least** common type had been _Gamble Violence_.

## Discussion:
- For our research question, **How has the crime rate in Washington State changed over the last twenty years?** It is important for us to know the rate in which the number of crimes has been changing over the years because knowing this trend can allow us to set goals in the future. Since the slope came out to be 5564, meaning 5664 more crimes per year, government could possibly set up a goal where they would implement a new policy and check at the end of the year to see if the number of crimes that occurred in that year was less than 5664.
- For the research question, **How much of the crime that happens in Washington is in or near Seattle?** This is important because although it may create bias and such while looking into the details of this data, but as students attending University of Washington, knowing the crime rates that occurs in or near Seattle is directly related to the safety of ourselves, and our friends and families (for some people) as well. It is also very important that knowing that King county is where the most of crimes in Washington happens, and a lot of it tends to be focused in Seattle area, there will be a need of actions taken by the city or the state.
- For our research question, **Did the crime get worse or better during the years we suffered from COVID-19?** it is important to note social movements occurring towards the beginning of 2020. In June of 2020 we see the rise of the Black Lives Matter movement and its protests that people took advantage of and committed crimes during. Since the peak of the movement in June we can see an increase of crimes but also the remnants of the beginning of the movement. It had a large impact on the population, positively and negatively and unfortunately, crime might have derived from that. Positively, we can see a decrease of crime towards our current day and hopefully that trend continues.
- For our research question, **What kind of or type of crime is most common in Washington State?** Asking such question and finding the answer was very important because without knowing what exactly, is the most common and least common types of crime, we can't clearly point out to the policymakers on how to.. or what to take a closer look into.

## Conclusion:
Before we sum up the report and call it a end, something that we believe is that there wouldn't be anyone out there who doesn't want to live in places where there is barely any crime. Less crimes could be directly related to better safety of the living environment of that place. However, we can't just conclude that the place is a bad place to live and is dangerous only looking at the number of crimes reported in the location. When it comes to finding patterns and specific answers using data, we must always know that there exist many other variables that comes into play a role in helping us to actually come up with patterns and answers. And because we specifically want ourselves, families, and friends to be safe living in Washington state (especially near Seattle), we have decided to look into the data about crimes in Washington state. After going through data analyzing, wrangling, visualizing, and etc with these datasets, we have learned so much about the crimes that occur in the Washington state. The main key takeaways that we would like to share is that there has been and always will be a positive trend with the number of crimes vs year if nothing changes. Especially now that we know theft, with motor vehicle theft as subcategory being the most common crimes in Washington state, I believe there should be like a state, city ran program that could protect people from the harms of this crime. It make sense that insurance exist for a reason, however, paying insurance to recover from theft seems to be a unfair thing as it is making a theft problem a individual problem rather than it being a statewide/citywide problem. Although, this is the case for Washington state from around 1990-2020, we strongly believe that something could be done by the state/city government to protect their citizens from not just physical harm but also from economic harms that are caused by vehicle thefts and all the others thefts. If this trend continues without any issues being addressed, then it is very likely that people who live in Seattle are less likely to own a car. This can result in businesses failing and in the end could even affect the funds that government has as it will definitely affect the economy of the state. And that is why we want to say that it is very important for government to make policies and act upon then in order to make their city/state a better, safer place to live and have people spent more money rather than being scared to get their things stolen. This is especially important during the times of pandemic and/or other social movements because when looking into our findings from trend during COVID question, we were able to find that during such times, the number of crime tends to increase and reaches peak (of its time). We believe that this is the case due to people losing their jobs, and being affected by social movements. Here the problem is no longer a criminal vs citizens it can become a citizen vs citizen as such events caused a well, fine person to start causing troubles for their survival. And that tells us that this is an issue that government could possibly help address. If it was guaranteed for the people to not get fired, or be affected economically from these events, there is a chance that those who committed crimes for the first time during these events wouldn't have done it. 

## Acknowledgement:
We would love to thank our TA Manu who was very understanding.

## References:
- Data. Washington State Statistical Analysis Center. (n.d.). Retrieved October 31, 2022, from https://sac.ofm.wa.gov/data
- Spd. (2022, October 31). SPD crime data: 2008-present: City of Seattle open data portal. Seattle Open Data. Retrieved October 31, 2022, from https://data.seattle.gov/Public-Safety/SPD-Crime-Data-2008-Present/tazs-3rd5

- Crime. (n.d.). Retrieved October 31, 2022, from https://crime-data-explorer.fr.cloud.gov/pages/home
- Ucl. (2022, August 13). UCL Hazard Centre. Retrieved October 31, 2022, from https://www.ucl.ac.uk/hazard-centre/sites/hazard_centre/files/wp9.pdf
- Take online courses. earn college credit. Research Schools, Degrees &amp; Careers. Study.com | Take Online Courses. Earn College Credit. Research Schools, Degrees &amp; Careers. (n.d.). Retrieved October 31, 2022, from https://study.com/academy/lesson/identifying-criminal-justice-stakeholders.html
- Kamb, L. (2020, November 24). Washington's rising hate crime numbers in latest report tell only part of the story, experts say. The Seattle Times. Retrieved October 31, 2022, from https://www.seattletimes.com/seattle-news/washingtons-rising-hate-crime-numbers-in-latest-report-tell-only-part-of-the-story-experts-say/

## Appendix A: Questions