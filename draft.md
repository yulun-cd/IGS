# 1. Introduction

Particulate matter (PM) refers to small solid and liquid matter suspended in the air, and is one of the most serious threat to human health among all the ambient air pollution. High exposure to PM can cause damage to human body including lung (Löndahl *et al.*, 2006), heart (Sun *et al.*, 2010; Brook *et al.*, 2010) and airway (González-Flecha, 2004), depending on the size of the particle. PM is mainly classified into two categories according to their aerodynamic diameter (Kim *et al.*, 2015), namely fine particulate matter (PM~2.5~), which has a diameter smaller than 2.5 μm, and coarse particulate matter (PM~10~), which has a diameter between 2.5 to 10 μm. The sizes of PMs decide their transport abilities in the atmosphere as well as in the human body. PM~2.5~ tends to travel longer in the atmosphere and penetrate deeper in the human body than PM~10~. As a result, major health problems related to PM~2.5~ are associated to lungs, Bronchi branches and Bronchioli (Löndahl *et al.*, 2006), while PM~10~ mainly causes damages to respiratory systems (airway) (González-Flecha, 2004). It is estimated that more than two million deaths worldwide each year are directly related to diseases caused by air pollution, most of which by fine particulate matter (Shah *et al.*, 2013). PM~2.5~ is the primary contributor to human health issues relating to ambient air pollution.

The hazard mainly comes from exposure to high concentration of PM~2.5~, and the lower the concentration, the less the danger it exposes to human health. The WHO guideline values for PM~2.5~ is 15 μg/m^3^ daily mean and 5 μg/m^3^ annual mean (WHO, 2021). This guideline represents the highest possible concentration to which the effect from PM~2.5~ to human health is acceptable, but does not guarantee no damage to health. However, most regions around the world, especially regions in developing countries, have PM~2.5~ levels higher than the WHO guidelines (World Bank, 2017). 

The fine particulate matter in the atmosphere comes from both anthropogenic and natural sources. The former include combustion of fossil fuels, industrial and agricultural activities, and erosion of pavement by road traffic (Srimuruganandam and Nagendra, 2012). The natural sources include volcanoes, wildfires, dust storms and sea spray (Anderson *et al.*, 2012). Natural sources contribute only 18% to global PM~2.5~ pollution,  with the rest from anthropogenic sources, among which traffic section takes up the highest percentage (Karagulian *et al.*, 2015). Hence, finding a way to mitigate the PM~2.5~ pollution from road transport emissions can greatly reduce the PM~2.5~ level in urban areas.

One proposed approach to this is developing near-road greenspaces. Many researches have examine the effect of greenspaces in reducing regional PM level (Kończak *et al.*, 2021; Song *et al.*, 2015; Lei *et al.*, 2018; Irga *et al.*, 2015; Hofman *et al.*, 2016), which is mainly through two mechanisms - mass removal and transmission block. On one hand, vegetation in greenspaces can help directly remove the PM from the air by capturing and storing them on the leaf surface as well as in the wax layer (Kończak *et al.*, 2021). On the other hand, greenspaces can act as a 'windbreak' that interrupts the dispersion of particulate matter (Morakinyo and Lam, 2016) as well as altering other local meteorological environments including temperature, barometric pressure, relative humidity, etc. which also affect PM level (Hofman *et al.*, 2016). 

Based on these theoretical and empirical foundations, near-road greenspaces are believed to have positive effect in lowering PM concentrations. Indeed, there have been studies finding near-road air quality being significantly improved by vegetation (Morakinyo and Lam, 2016), especially in busy roadsides in open areas (Baldauf *et al.*, 2011). However, Vos *et al.* (2013) found that in some cases, instead of reducing PM~2.5~ concentration, roadside vegetation can actually enhance PM pollution nearby by hindering the wind flow and resulting in an accumulation of particulate matter in the area (Abhijith *et al.*, 2017). Such a finding brings uncertainty to the effect of near-road greenspaces on lowering PM~2.5~ level in urban areas, and further investigation is needed.

Previous researches on examining the effect of greenspaces, especially near-road greenspaces, in reducing PM concentration in urban areas can be divided into two streams. The first stream primarily focused on assessing the abilities in capturing particles in the air of greenspaces with different characteristics. Liu *et al.* (2015) found that canopy density, leaf area, mean diameter at breast height, average tree height and grass coverage and height in forests could greatly alter PM~2.5~ concentration. Different vegetation species also have different levels of impacts on PM concentrations. For example, cypress trees reduce PM level more than pine trees (Ji and Zhao, 2014). Variations in the location of vegetation in relation to wind direction can also lead to changes in its ability to reduce PM concentrations (Al-Dabbous and Kumar, 2014). Greenspaces are most effective in reducing PM concentrations when the wind blows from areas of high PM level (e.g. roads) towards them. Lei *et al.* (2018) found that patterns of greenspaces can also influence their ability to reduce PM pollution. Increasing the differences between areas of greenspace patches as well as their edge complexities can significantly lower PM concentrations. These research findings contribute extensively to the academic understandings and policy-making of the urban greenspaces in tackling PM pollutions. However, most of them failed to consider temporal changes. PM~2.5~ concentrations in different seasons can vary greatly, and even within one day the concentrations have highs and lows. In these cases, the influences of greenspaces on PM concentrations could also be changing. Moreover, most of these studies' approach was through field measurements, which, while delivering valuable first-hand data and solid mechanism-level understandings, were not convincing enough if were to be applied to a larger scale.

The other stream that includes this subject used land use regression (LUR) extensively to examine how land use types affect spatial-temporal changes of PM~2.5~ levels. Wu *et al.* (2017) utilized a LUR model with PM~2.5~ concentrations and monthly Normalized Difference Vegetation Index (NDVI) data in Taipei, and found a strong negative correlation between them. Xu *et al.* (2019) also found a relation between forest land type and PM~2.5~ level through LUR. However, the problem with LUR technique is that it always suffers from multicollinearity (Ross *et al.*, 2007), which makes the model output less reliable. To overcome this, Kim (2020) developed a partial least-squares regression model, which minimizes the influence of multicollinearity of the variables, to study the effects of land use on PM levels in different seasons in Seoul, South Korea, and found that the percentage of greenspace area is negatively related to regional PM concentrations. Yet, none of them was able to evaluate the relation between near-road greenspaces and regional PM~2.5~ concentrations.

Therefore, although urban greenspaces have been proven to have significant effect on PM reduction, the influence of near-road greenspaces and its temporal changes are still not clear. Given the fact that road traffic is the largest contribution to PM~2.5~ pollution in most parts of the world (Karagulian *et al.*, 2015), it is important to determine whether near-road greenspaces have a positive or negative effect on reducing PM concentrations. Hence, this study aims to examine the role of near-road greenspaces with regards to PM~2.5~ concentrations, taking London as a case study city. To be more specific, PM~2.5~ data from 21 selected air quality monitoring sites across London were used to examine the relationships between different types of near-road greenspaces and PM~2.5~ concentrations as well as the temporal changes of the relationships. It is recognised that greenspaces that are near different types of roads will have different effects in reducing PM concentrations, so the near-roads greenspaces were classified into several categories according to their road types. The result of this study can enrich the understandings of near-road greenspaces' effect in lowering regional PM~2.5~ concentrations and its temporal change, and inform local urban planning.

# 2. Methods

### 2.1 Background

London has a population of approximately 9 million and covers a land area of around 1500 km^2^. It is the largest city in the UK and has one of the busiest road traffic in the country. It is characterised by a temperate oceanic climate, with warm to hot summer and cool winter, and high precipitation all year. 

##### PM~2.5~ pollution in London

The annual average PM~2.5~ level in London was reported as 13.3 μg/m^3^ in 2016 (Mayor of London, 2019), which was above the WHO guideline for annual mean concentration (5 μg/m^3^). It is estimated that apart from transboundary sources, the largest proportion (30%) of the PM~2.5~ pollution comes from the road transport section (Mayor of London, 2019). In areas with intensive traffic flow (e.g. central London), the PM~2.5~ may be much higher than the annual average level.

##### Air Quality Monitoring in London

London has one of the largest air quality monitoring networks in the world, with participations from all kinds of organisations and departments. The London Air Quality Network (LAQN) is one of them and is operated by the Environmental Research Group at Imperial College London, in cooperation with TfL (Transport for London), Defra (Department for Environment, Food and Rural Affairs) and local authorities where the monitoring sites are located (London Air, 2022). It provides the public with open air quality data collected from its monitoring sites all across London. Apart from LAQN, the Automatic Rural and Urban Network (AURN) is another network that provides nationwide hourly air quality data to the public (Defra, 2022), with several sites in London. 

The richness of the air quality data is a very important reason for choosing London as the case study city. The spatial change of PM~2.5~ concentrations across London is a very important dimension of this study, hence it is crucial to gather data from different monitoring sites.

##### Road classification

The roads in London (and the UK in general) are classified into four categories (GOV.UK, 2012):

1. A roads - major roads aiming to provide transport links within or between areas. This type of roads should have the highest volume of traffic among the four.
2. B roads - a lower class of roads, often with poorer physical standard. Intended to feed traffic between A roads and smaller roads
3. Classified unnumbered - smaller roads connecting A, B roads with unclassified roads. Also known as C roads
4. Unclassified - local roads supporting local traffic. Most roads in the UK fall into this category. This class of roads should have the lowest volume of traffic.

Except for those four categories, motorway is another category of roads that provide high-speed long distance transportation. The number of motorways is much lower than other four types of roads.

##### Greenspace in London

London is a green city, with roughly 40% of its area being greenspaces. However, the greenspaces are not evenly distributed across the whole city, with a much larger portion in Outer London and a smaller portion in Inner London. The uneven spatial distribution pattern gives an opportunity to study its relationship with regional air quality, and in this case, with regional PM~2.5~ levels.

There are currently two schemes to protect the urban greenspaces in London, with one focusing on protecting undeveloped land around the city called Green Belt and the other aiming to protect greenspaces within the city called Metropolitan Open Land (MOL). The two designations helped develop and maintain extensive urban green areas in London. 22% of London is specified as Green Belt and another 10% is specified as MOL (GiGL, 2018).

### 3.2 Data

##### PM~2.5~ data

Hourly mean PM~2.5~ concentration data from 21 air quality monitoring sites across London were downloaded from the London Air website, which is the website of the LAQN. Most of the sites are in the LAQN and the others are in the AURN. The 21 selected sites locate mainly in the Inner London, with 2 of them in the Outer London. **Fig 1** shows their locations.

The hourly mean PM~2.5~ concentration data is for the year of 2019, which is the most recent pre-COVID year. 

### 3.3 Data pre-processing and EDA

### 3.4 Model

# Results

