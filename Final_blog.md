# Final blog (designer): Housing and Spatial Inequality in Chicago

## Introduction
In an effort to provide support and opportunity for lower-income individuals, the city of Chicago and other organizations have commissioned affordable housing developments for qualifying individuals. With parks often posed as a threat of gentrification and green spaces seen as more desirable (Rigolon and Christensen), I think it would be interesting to explore how parks and affordable housing units relate to the city's community by asking the question: How do housing units and parks relate to the social and economic inequality in Chicago?

### Data
The data used come from the Chicago Data Portal. These include [Census Data - Selected socioeconomic indicators in Chicago, 2008 – 2012](https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2), [Parks - Chicago Park District Park Boundaries (current)](https://data.cityofchicago.org/Parks-Recreation/Parks-Chicago-Park-District-Park-Boundaries-curren/ej32-qgdr), and [Parks - Chicago Park District Facilities (current)](https://data.cityofchicago.org/Parks-Recreation/Parks-Chicago-Park-District-Facilities-current-/5yyk-qt9y).

## Visualizations
### Plot 1-1
![map plot 1](images/map1_final.png)

This first plot is aimed at displaying where the affordable housing units and parks are located in the city. It appears that there are parks distributed in the unit-dense areas and how many units do not appear to impact how many parks. Most housing units seem to be in the center and the north side of the city.

### Plot 1-2
![map plot 2](images/map2_final.png)

This next plot displays the percentage of household poverty by neighborhood. There seem to be parks distributed well throughout each area. However, there are a couple of areas where the percentage of household poverty is the highest and there are not too many parks present as compared to other areas. Comparing this plot to the first, there seem to be affordable housing units in the areas with a higher percentage of household poverty in the center of the city but not in the areas farther south.

### Plot 2-1
![property type plot](images/property_type.png)

This next plot displays the number of units from each affordable housing property type and the different colors in the plot represent different community areas. ARO is the government-provided affordable housing and it is clear that it does not make up the majority of affordable housing units in Chicago. The types of property units seem to be somewhat evenly distributed across each part of the city.

### Plot 2-2
![community and property type plot](images/community_type.png)

This plot gives a closer look at where these different types of units are located throughout the city. 

### Plot 3
![capita and communities plot](images/econ_com_plot.png)

This next plot then displays the percentage of household poverty in each community. Grand Boulevard, which has the most amount of units as seen in the previous plot, is about midway between the highest and lowest percentage of household poverty just being slightly lower than 30% of households. 

### Plot 4-1
![housing and income plot](images/housing_income_plot.png)

This next plot does not seem to have a relationship between the number of parks and the average income per capita for each neighborhood. 

### Plot 4-2
![parks and income plot](images/parks_income_plot.png)

In the following plot, there doesn’t seem to be a relationship between the number of affordable housing developments and the average income per capita by the community. However, there may be more units located in lower-income per-capita areas. 

### Plot 5-1
![units and capita plot](images/capita_units.png)

This next plot displays that Near North Side has a lower median of units per property but more properties while Riverdale has a higher median of units but fewer properties. 

### Plot 5-2
![park and capita plot](images/capita_parks.png)

For parks, Near North Side appears to have more parks with fewer acreage while Riverdale has fewer parks with slightly more acreage.

### Plot 6-1
![senior housing units plot](images/senior_units.png)

This next plot focuses on senior and intergenerational affordable housing and displays a very slight relationship between the number of units and percent of under 18 and over 65 people per neighborhood. 

### Plot 6-2
![senior units and parks plot](images/senior_units_acres.png)

In this plot, there is a slight positive relationship between the number of units for senior and intergenerational affordable housing and the number of acres of park space. 

### Plot 6-3
![seniors and parks plot](images/senior_acres.png)

However, there does not seem to be a relationship between the number of park acres and the percentage of people under 18 and over 65. 

### Plot 7-1
![units and crowded housing plot](images/crowd_units.png)

This plot displays a slight positive relationship between the number of housing units per property/the number of properties and the percentage of crowded housing. 

### Plot 7-2
![parks and crowded housing plot](images/crowd_parks.png)

However, there does not appear to be a relationship between the acreage per park/number of parks and the percentage of crowded housing. 

### Plot 8
![desnity units and acres plot](images/unit_acres.png)

It appears from this plot that most housing units tend to be in areas with less than about 4000 acres of park. 

### Plot 9-1
![welfare index and housing units](images/index_housing.png)

The distribution of units is similar for all levels of the hardship index, with the lowest index having the most properties but presumably with fewer units. However, most ARO (government-commissioned) units tend to be in areas with lower levels on the hardship index. 

### Plot 9-2
![welfare index and parks](images/index_acreage.png) 

The distribution of park acreage throughout all the levels of the hardship index tends to be similar.

## Conclusion
There does not appear to be that strong of a relationship of the locations of affordable housing and parks with social and economic inequality in the city from the variables I explored. More affordable housing units seem to tend to be in areas with more overcrowding, there are less affordable units and parks in areas farther South in Chicago, and the type of housing differs in neighborhoods with different indexes of hardship. More exploration will have to be done to help answer my question, but these visualizations can provide a base to understand the distribution of affordable housing and parks in Chicago.

### Citations
Rigolon, Alessandro and Jon Christensen. 2019. "Greening Without Gentrification". National Recreation and Park Association. 
[https://www.nrpa.org/parks-recreation-magazine/2019/december/greening-without-gentrification/](https://www.nrpa.org/parks-recreation-magazine/2019/december/greening-without-gentrification/)

Map shape file from [Intro to Making maps with ggplot2](https://thisisdaryn.netlify.app/post/intro-to-making-maps-with-ggplot2/)


