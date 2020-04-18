 # Geospatial Data Methods of Analyzing Child Malnutrition Among Disaster
 
Brianna Williams

### Introduction

Nutrition is a quintessential sustainable development goal. Malnutrition is often the most relevant cause of child mortality in developing countries.  Child malnutrition can be a cause of long-term effects such as inadequate dietary intake and diseases, as well as short term effects like natural disasters and political turmoil. In its earnest definition, inadequate dietary needs cause child malnutrition; specifically, obesity rates due to the influx of an unhealthy diet and undernutrition due to insufficient nutrients and lack of food supply. 

For this research, the focus is mainly on child undernutrition in the researched countries. Affecting nearly 900 million people worldwide, undernutrition is responsible for the highest mortality rate in children. Lack of adequate quantity and quality of food is an issue deemed so important because it negatively affects developing countries and poor populations the most. 

Apart from the bodily effects, undernutrition can affect these developing economies due to the high prevalence of the issue and its ability to perpetuate poverty. The undernutrition effect works like the Domino Effect: once someone undergoes the conditions of undernutrition, they are unable to perform to the highest standard due to their poor physical conditions, and thus hindering their cognitive abilities and education. In turn, these factors affect economic development in these low income countries. 

In 2010, Haiti suffered from a 7.0 magnitude earthquake with an epicenter at Léogâne and affected nearly 3 million Haitian people. As an immediate effect of this natural disaster, child malnutrition became a relevant developmental issue in Haiti. The disaster substantially impacted sectoral conditions such as drinking water, sanitation, energy/fuel, food supply, healthcare, and clearing of debris by the disaster. Hence, these conditions note to have a disruption on the direct development of Haiti and stunted the process.

Undernutrition is a complex issue in many ways. Various factors can be the ultimate reason why a country is struggling with nutrition rates. As seen in Balk’s research, household differences, environment, and socio-economics all have an impact on the availability of food which coincide with Amartya's idea of how an income increase can benefit the development of a society (Balk et al). In an attempt to investigate the effects of geographic and environmental factors that affect child nutrition, Balk uncovered that vaccinated and breastfed children are impacted less. Likewise, those located near areas with fertile soil, potable water, and suboptimal levels of agriculture were also impacted less. However, natural disasters add an outside effect as to why various developing countries are struggling with child mortality rates due to undernutrition. In Haiti specifically, humanitarian aid focused heavily on combating this issue and actually saw a decrease in these rates during recovery from the disaster. Yet, nearly 4 months later, researchers uncovered that the conditions needed to improve nutrition and health care in the country improved significantly (i.e., drinking water, health care) (Brink et al). Nutrition in these countries is ever so complex and can easily be affected by the factors stated above. 

To further investigate and quantify the harms of undernutrition to improve rate of child malnutrition in developing countries, I have analyzed Mohamed’s SMART survey data methodology and Andrea Spray’s research for the comparison of geographically weighted regression and ordinary least squares regression models. These two researchers use survey data to further enhance the accuracy of child malnutrition rates in Haiti, especially in terms of the earthquake. 

### Inquiry Type     

Wondering how natural disasters have affected the rates of child undernutrition in developing countries can be identified as both an exploratory and explanatory inquiry. In the beginning of my research, I was under the impression that the cause of these rates was from underlying effects in Haiti’s healthcare and education system. While this fact remains true, research has shown the earthquake has also had an effect on the process of improving these rates. Hence, I seek to understand how various factors like household conditions affect these rates. Beyond that, I seek to investigate if these rates are changing positively or negatively after the earthquake, especially since humanitarian aid efforts flooded in following the earthquake. These two questions require complex answers, though. Because child malnutrition is so prevalent in Haiti, efforts focused on the improvement of these rates following the earthquake. Yet, it is evident that more than humanitarian efforts following a natural disaster improved the statistics. The improvement of other sectoral conditions like drinking water, sanitation, and healthcare is required, yet hindered following the earthquake. If such humanitarian efforts focused on creating a larger food supply, how were other sectoral factors that impact this nutrition rate treated through aid efforts? This event introduces the idea that there is a causation relationship between natural disasters and household/living conditions to undernutrition rates amongst children in developing countries.  

### Method 1: Spatial Video     

 In Curtis' article, “A ubiquitous method for street scale spatial data collection and analysis in challenging urban environments: mapping health risks using spatial video in Haiti,” the authors composed a fine-scale geospatial research analyzing health risks in developing urban areas. The case study ultimately maps out health risks within the coastal communities of Haiti--the specific areas where the earthquake hit. On June 26, 2012, the researchers planted 4 high definition cameras on a vehicle and drove through Haitian communities affected. Following the videotaping of the communities, data was then coded. In this step, they describe the process as a creative process. They were able to distinguish obvious attributes to various health risks; for example, the amount of trash in the community, the depth of flood water, and inadequate infrastructure. They considered all main roads and planted them on a coordinate path that was extracted from “Storyteller software and displayed on Google Earth to check for complete spatial coverage” of the area (10). They coded the information and analyzed the video for any errors prior to uploading to Google Earth. They then evaluated spatial video to collect information regarding water, trash accumulation, and other covariates that identify population and other cultural phenomena. The data was later digitized into Google Earth then interpreted into a GIS and spatial filtering approaches. Once coding was complete and imported into ArcGIS, they were able to analyze the information accordingly. They visualized the data using a kernel density analysis. The authors state that this is often used in public health to “gauge spatial patterns of a single variable independent of artificial boundaries” (11). Hence, they were able to investigate the depth of water in the area (Reference *Figure 1*). With this information, kernel density heat maps were created to receive general information about the population. The authors then explain that this data can be used in Geographical Weighted Regressions to analyze various diseases and nutrition rates in developing areas (Curtis).

#### Results

Through the usage of spatial video and GIS, the researchers were able to map various factors that can cause extreme health risks in Haiti. They found that there were heavily concentrated sources of diarrheal disease, which is quite prevalent in children affected by malnutrition. Similarly, they found concentrated areas near schools, which is prevalent for cholera education prevention. Overall, their results yielded that health risk data vary in concentration, however schools ran a high risk in contracting these health risks, or hot spots. They concluded that the spatial video method is beneficial in identifying health risks, such as child malnutrition, in order to improve the area or allocating resources. The process is described as rapid and can be repeated a number of times. 

### Method 2: Geographically weighted regression, ordinary least squares regression models, and bivariate analysis     

 In Spray's article, “Spatial analysis of undernutrition of children in Léogâne Commune, Haiti,” the researchers used household surveys using a “modified 33 × 6 alternative sampling design” from 2008 and 2010. Researchers gave households with children ranging from 6 to 35 months in age. Clusters of 6 households were randomly assigned using Haiti’s 2003 census data. The survey was divided into a holistic household survey, and a youngest child specific survey. The sample for the child survey used 150 children spanning across 33 communities. It is important to note that GPS locations were not collected while analyzing the data, thus multiple regression analyses were used to create the sample size. Cases that contributed to undernutrition were analyzed in 3 phases: a bivariate correlation, OLS regression, and GWR. Factors mainly analyzed in the research include: “household food insecurity, inadequate care, unhealthy household environment, and lack of health services” (446). The researchers state that the variables analyzed amongst these factors were a household dietary diversity score (HDDS), care practices, primary water sources, illnesses prevalent, distance from health care facilities, ability to travel to these healthcare facilities, and vitamin A supplementation during the past 6 months.       

The OLS regression model was expanded to comprehend which variables were most important to each community. By using a backwards step down method, they analyze each explanatory variable and their nutrition outcomes. A backwards step down method removes each variable that is deemed the least significant, and continually does so until no non-significant variables remain. Hence, the researchers state that the "OLS regression results in a single model that generalizes all information throughout the 33 communities." In result, OLS regression oversimplifies information received from the communities in the survey sample.      

GWR was used to compare the results from the OLS regression to see which one was more effective and reliable. The same variables used in the OLS regression were also used in the GWR analysis. Following the 2010 earthquake, the researchers used geographic information system base maps to map topographic factors using data from Haiti Earthquake Data Portal. Geographical information included was collected from Google Earth. The researchers used various statistical software, such as STATA/SE, version 11 in order to evaluate descriptive statistics and bivariate correlation. Likewise, “OLS regression and GWR was conducted using the ArcGIS Spatial Analyst extension (ArcGIS, version 10). A probability of p ≤ .1 was accepted as the level for statistical significance” (447). *Figure 4* below presents the nutritional distribution among the children in Léogâne, Haiti. ().

#### Results

The author’s found that children stunted were measured to be roughly 23.3% of the study population, 8% were underweight, and wasting was 2% (447). The results from the bivariate analysis suggest that household environment, access to health services, and illnesses contribute the most to child malnutrition in Haiti. The other factors stated previously contributed to acute malnutrition statistics within the communities. Spatial factors, such as distance from water and health care facilities were deemed insignificant to nutrition statistics. According to the researchers, all models were deemed beneficial in determining the factors. The OLS model was compared to the GWR model: “The AICc of the GWR model was 75.24, compared with an AICc of 52.09 for the OLS model. The overall *R*-squared of the GWR model was 0.66, an improvement over the *R*-squared for the OLS model of 0.55” (454). Through this evidence, it was proven that the GLS was not statistically better at predicting nutrition rates than the OLS model. According to the OLS model, undernutrition occurs in “pockets'' rather than being evenly distributed throughout the community. Therefore, the researchers establish a gap within their research. They believe this result is because of the small sample sizing once the data was aggregated and that if GPS locations were collected, GWR would work more efficiently. Despite this limitation, the authors are confident that geospatial techniques and regression models to analyse child malnutrition rates are ever evolving. 



### Method Comparison and Research Gaps      

As stated in the first article, one of the main United Nations Millennium Development Goals (MDGs) is addressing health risks associated with informal settlements. This idea is similar to Haiti’s developmental goals of improving health services and improving food security. The researcher’s methods explain how spatial video can provide a more accurate and updated method of fine-scale data input layer suitable for inclusion in other modeling frames. Or, in other words, whether it can be used to make a spatial risk assessment for evaluating traditional disease related variables, and map nearby schools in the community. Using spatial video maps allows them to view the various poor conditions via a reliable source. In contrast, the second method compares various regression models using survey data in hopes to find a more accurate resource. OLS, GWR, and bivariate analysis are proven to be sufficient regression models for estimating child malnutrition rates. It is evident that one method uses very accurate spatial video and coding analysis, while the other uses sampling techniques to great statistical models. Regardless of the previous gaps in research stated individually in their results section, both methods are effective in evaluating the child malnutrition factors (explanatory inquiry) and the effects the earthquake had on nutrition rates (exploratory).       

My central research question is “how do sectoral conditions further affect child malnutrition rates in developing countries who are recovering from natural disasters?” Thus far, research gaps I have encountered throughout this process was finding conclusive data with no shortcomings (DHS data) and geospatial methods that pertain solely to child undernutrition in Haiti. In the future, more geospatial data could be collected surrounding nutrition rates in affected countries. 

### Figures

*Figure 1*

![Figure 1](https://www.researchgate.net/profile/Jason_Blackburn/publication/236183994/figure/fig1/AS:195704636088331@1423671029670/Examples-from-the-spatial-video-Storyteller-software-showing-two-of-the-health-risks_W640.jpg)


*Figure 4*

![Figure 4](https://pbs.twimg.com/media/EV3LcBJXsAAaZ0f?format=jpg&name=medium)


*Figure 5*

![Figure 5](https://pbs.twimg.com/media/EV3LaddWsAI8MaX?format=jpg&name=medium)




*****

**Word Count: 2181**

*****

### References
[1] Balk, D., Storeygard, A., Levy, M., Gaskell, J., Sharma, M., & Flor, R. (2005, November 10). Child hunger in the developing world: An analysis of environmental and social correlates. Retrieved from <http://www.sciencedirect.com/science/article/pii/S0306919205000886>

[2] Brink, S., Chang, S., Eguchi, R., Davidson, R., Amyx, P., Pyatt, S., … Honey, M. (2010, October 1). Assessing Community-scale Damage, Disruption, and Early Recovery in Post-earthquake Haiti. *University of Delaware Disaster Research Center.* Retrieved from <http://udspace.udel.edu/handle/19716/5851>

[3] Curtis, A., Blackburn, J. K., Widmer, J. M., & Jr, J. M. (2013). A ubiquitous method for street scale spatial data collection and analysis in challenging urban environments: mapping health risks using spatial video in Haiti. *International Journal of Health Geographics,* 12(1), 21. <https://doi.org/10.1186/1476-072X-12-21>

[4] Spray, A. L., Eddy, B., Hipp, J. A., & Iannotti, L. (2013). Spatial Analysis of Undernutrition of Children in Léogâne Commune, Haiti. Food and Nutrition Bulletin, 34(4), 444–461. <https://journals.sagepub.com/doi/abs/10.1177/156482651303400410#articleCitationDownloadContainer>

