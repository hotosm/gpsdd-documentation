---
title: Goal 2 - Zero Hunger
weight: 2
---

## End hunger, achieve food security and improved nutrition and promote sustainable agriculture

_“Our soils, freshwater, oceans, forests and biodiversity are being rapidly degraded. Climate change is putting even more pressure on the resources we depend on, increasing risks associated with disasters such as droughts and floods. Many rural women and men can no longer make ends meet on their land, forcing them to migrate to cities in search of opportunities.”_

Understanding where things are located through maps, allow us to where things are not. For food security, this can allow governments and NGOs to see where food deserts exist, gaps in food distribution and assistance centers are occuring, and for policy makers to understand where and what farmers are growing to conduct thorough outreach, assistance, and training. 


### What has been done? 

**[Engaging Youth in Mapping Agriculture and Food Security](http://www.kathmandulivinglabs.org/projects/engaging-youth-in-mapping-agriculture-and-food-security)** - Kathmandu Living Labs trained local students, youths and farmers to map their village in OpenStreetMap. Villages were mapped to assist in government agricultural policy. Farmers used open tools to map crops to understand what is grown where, and what markets are available. 

**[Building resilience of agricultural communities:](https://www.hotosm.org/projects/openstreetmap-colombia)** Recently, agricultural communities in Colombia have suffered due to devastating earthquakes and high volumes of landslides during rainy seasons. Fundación OpenStreetMap Colombia are collaborating with local government and local organisations on the Countryside Mappers Program. In partnership with the local government, Unidad de Mapeo Humanitario and OSM Colombia will help build risk management and evacuation plans.


### What else could be mapped?



*   Map access to food, such as household garden plots, outdoor markets, and grocery stores in order to identify food deserts
*   Map food distribution and assistance centers
*   Landuse and agricultural information such as crop types and seasonality
*   Map marketplaces and their products to assist farmers with planning
*   Map farms to guide NGOs and government agencies in reaching farmers for assistance and training opportunities 

### OSM Data Model

|  Category | Key | Value | Description/notes |
| --- | --- | --- | --- |
|  All facilities | name |  | *Name of facility* |
|   | noname | yes | *If no name* |
|   | opening_hours | <opening hours> | *Hours of operation* |
|   | addr:full | <free text> | *Full address<br/>and/or addr:city, addr:district, addr:street, etc.* |
|   | wheelchair | yes, no | *Wheelchair accessibility* |
|   | contact | <free text> | *Contact information for food resource* |
|  Food shops | shop | supermarket, farm | *Used as a place of business that has stocked goods for sale.* |
|   | amenity | restaurant, cafe | *If a food amenity, used to describe the type of facility.* |
|   | cuisine | [<free text>, see wiki for suggested values](https://wiki.openstreetmap.org/wiki/Key:cuisine "<free text>, see wiki for suggested values") | *For describing the type of food served at an eating place.* |
|  Distribution centers, food banks, pantries | amenity | social_facility | *Used to identify an amenity used for social services.* |
|   | social_facility | food_bank, soup_kitchen, community_centre, reception_centre, transit_centre, distribution | *For describing the type of social services provided.* |
|   | social_facility:for | community, refugees, child | *For describing the target population used by the social facility.* |
|   | operator | <free text> | *Name of operator* |
|   | operator:type | public, private, religious, ngo | *Type of operator* |
|  Markets | amenity | marketplace | *Used to identify a facility used for selling goods and services on a regular basis.* |
|   | marketplace:type | <agricultural, clothes,mixed> | *For describing the type of goods and services offered at a marketplace.* |
|  Community gardens | leisure | garden | *Area of land used for residential or public cultivation.* |
|   | garden:type | community, residential, roof_garden | *For describing the type of garden.* |
|   | access | yes, no | *For describing the public accessibility of a garden.* |
|  Farms | landuse | farmland, orchard, plant_nursery, aquaculture, forest | Area of farmland used for tillage and pasture (animals, vegetables, flowers, fruit growing) |
|   | crop | grass, wheat, cassava, coffee, <other> | The crop produced by cultivated land |
|   | produce | fish, apples, live_animal | Agricultural output, alternate to crop=* |
|   | animal | cattle, buffalo, sheep, goat, pig, horse, <other> | Used to specify features related to a type of animal |
|  Office | office | <association,company, government, lawyer, ngo, political_party, telecommunication> | *Used to identify a place of business or service used for administrative or professional work.* |
  <br>
  Additional resources: https://wiki.openstreetmap.org/wiki/Food_security
