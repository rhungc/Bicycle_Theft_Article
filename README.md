# What Factors Contribute to Toronto Bicycle Theft?

STA313 Assignment 2
Ruei-Hung Chen; Zhenyu Xuan
Every year in Toronto, there are a great number of bike stolen cases reported to the Toronto Police
Service. To help the general cyclist community mitigate the risks, our group analyzed the data
from the Public Safety Data Portal and focused on analyzing the risk factors potentially associated
to bike theft.

## Premise type Assessment
Firstly, we decided to focus on analyzing the premise type of the reported bicycle theft from the
Toronto Police Service database. Using the reported cases, we summarized the number of thefts
happened in each premise type and create this bar chart.


<img src = https://raw.githubusercontent.com/rhungc/Bicycle_Theft_Article/main/Premise_type.png> 

According to our summary, we noticed that lots of the bicycle thefts happened in personal
apartments and houses. If we combine the two together, bicycle thefts happened the most in
indoor environment, especially in local neighborhoods! Thus, we should zoom in and take closer
look to these premises by neighborhoods.

## Bike Theft Percentage
Next, we decide to explore the theft percentage by each neighborhood. We import the population
data in each neighborhood from “open data Toronto”. Ideally, we would want to obtain the total
number of bicycles in each neighborhood and use that to calculate theft percentage, however it is
unfeasible to obtain data as such. Since the bike is a means of transportation and it may always
move from one neighborhood to another. Thus, in the following analysis, we make an assumption
that for the same size of population, the number of persons who uses bike in daily life is identical.
Therefore, we estimated it by using the number of bike theft cases divided by the population in each
area. we regarded the percentage less than first quartile (< 0.00175) as Low-Level, first quartile
(>=0.00175) to third quartile (< 0.009) as Medium-Level and the percentage greater than (>=
0.009) as High-Level. By calculating the bicycle theft percentage in each neighborhood, we would
be able to learn which neighborhoods are considered high risk in bicycle theft.

<img src = https://raw.githubusercontent.com/rhungc/Bicycle_Theft_Article/main/theft_percentage.png>

We used luminous color (Red) from the darkest to lightest to stand for High level to Low level
respectively. As our graph suggested, the percentage of bicycle theft is high in the Southern part
of the GTA. This may suggest that people who live in this part of the region should pay extra
attention to securing their bicycle storage at home to prevent the lost of their bicycle.


## Bike Theft Percentage + Bikeways
Looking back to the first graph that summarized the bicycle thefts in different premises, we saw
that the second highest bicycle thefts occurred in the outdoor environments. We hypothesized that
these thefts happen while people were commuting from one place to another. Therefore, we decided
to study more carefully to regions where cyclists are most likely to show up.

We imported external data - “Bikeways” from Open data Toronto, in the hope to compare regions
with more bike routes and regions with less bike routes. Ultimately, we wish to understand whether
bike routes contributed in anyway to the bicycle theft percentage in the neighborhoods.

<img src = https://raw.githubusercontent.com/rhungc/Bicycle_Theft_Article/main/bike_routes.png>

In fact, as our visualization suggested, the area with the highest density of bike routes happen
to overlay with the area with high percentage level of bicycle theft. Previously, we find that the
Southern part of GTA is the area with the highest risk of bicycle theft in outdoor environment. We
can clearly get the conclusion that the higher the density of Bikeways is, the higher the risk levels
are for those areas.


## Bike Theft Percentage + Bike Parking place
Besides the bikeways, we look at more possible risk factors that contribute to high level of bicycle
theft in the Southern part of GTA. We hypothesized that if there is more bike parking lots in some
hoods, it’s more convenient for persons there to travel or commute with bikes. Also, in our opinion,
most bike theft cases happened during the parking time. The greater number of parking lots might
increase the risk level of bike theft.

Then, we imported external data - “Bike_Parkings” from Open data Toronto to study what resources
does the Toronto government provide the cyclists to store and park their vehicles.

We input all the parking types – angled bike rack, bike corral, bike rack, bike shelter onto the
neighborhood map of Toronto with risk levels.

<img src=  https://raw.githubusercontent.com/rhungc/Bicycle_Theft_Article/main/Parking_lots.png> 

As our data visualization showed, it’s obvious that almost all the bike parking areas are located
in the hoods with high risk level of bike theft. While the other hoods with scarce parking lots are
low in bike theft risk level. The graph verified our guess that the risk level of bike theft is higher
if there are more parking areas in those neighborhoods.


## Conclusion 
In conclusion, the Southern part of GTA is the region that experience the highest level of bicycle
theft. Cyclist who travels to or live in the Southern GTA neighborhoods should be more careful
due to the high-level bike theft risk. There are several factors lead to this situation, such as the
high density of bike ways, the greater numbers of bike parking lots etc.

The bikes stolen cases mostly happened during both the outdoor and indoor parking time. In
order to mitigate the risk of bike theft outside, although the government has done some things
to help cyclists to store and park their bicycles while they are out, there’s still a lot of room for
improvements. For example, some of the highly used bike routes in the Southern GTA does not
have facilities for cyclists to store their bicycles at all! So, we believe that if the facilities can be
implemented at least evenly into the neighborhoods, it could dramatically improve the bicycle theft
level in the Southern GTA area. In addition, for the bike theft cases happened indoor, the general
cyclists should store their bike in their garages in houses and increase the number of closed-circuit
televisions around the garage. With the improvement in monitoring and indoor security, the risk
of bike theft during indoor parking time will probably alleviate.

