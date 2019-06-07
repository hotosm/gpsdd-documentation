---
title: Goal 12 - Responsible Consumption and Production
weight: 12
---

## Ensure sustainable consumption and production patterns

_Sustainable consumption and production is about promoting resource and energy efficiency, sustainable infrastructure, and providing access to basic services, green and decent jobs and a better quality of life for all. Its implementation helps to achieve overall development plans, reduce future economic, environmental and social costs, strengthen economic competitiveness and reduce poverty._

![](/images/part-iv/waste_mapping.jpeg)

Approaching solid waste and consumption geospatially can help urban planners and governments understand distribution and patterns of waste and production issues their city faces. Addressing waste issues through participatory mapping allows community members to identify trouble spots for waste that might otherwise be overlooked and allows them to identify priorities for interventions. Additionally, mapping recycling centers and other positive impacts on the consumption cycle can identify where positive impacts are developing and where opportunities still exist. 


### What has been done?



*   **[Ramani Huria:](http://ramanihuria.org/tabata-trash-mapping-data-for-solid-waste-management-in-informal-settlements/)** The HOT Ramani Huria team worked with local waste company in Dar es Salaam to map buildings and customers using the open mapping workflow and OpenStreetMap. The experience showed that mapping all buildings and units, and providing information in an organized database format allows a collection firm to increase their revenue, and to make that revenue more predictable using OpenStreetMap. 
*   **[Clean Dhaka, Safe Dhaka:](https://boiledbhoot.org/)** Dhaka faces a tremendous challenge in terms of waste management. The ‘Clean Dhaka, Smart Dhaka’ project objective is to create a geo-database of waste disposal points in order to identify opportunities to make local urban waste management more sustainable and resilient through OpenStreetMap. This is currently a research project with the implementation, advocacy & activism phase upcoming. This project is initiated by the Bangladesh Open Innovation Lab (BOIL).


### What else can be mapped?



*   Map solid waste sites - both formal and informal - to understand how waste is being produced
*   Analyze proximity of waste sites to water points, waterways, schools, and other features to prioritize waste management
*   Map restaurants, markets, cafeterias, and other food consumption areas to survey food waste
*   Map recycling centers and businesses


### OSM Data Model

**1. Solid Waste Sites** <br>

|  Key | Value | Description/notes |
| --- | --- | --- |
|  amenity | waste_dump_site, waste_disposal, waste_basket | *Used for sites, features, and facilities were waste is unofficially or officially collected* |
|  landuse | landfill | *Used to identify land used as a landfill. * |
|  dump:official | yes, no | *Designates whether or not a site is officially recognized by authorities or waste collection agencies/companies* |
|  waste | trash, plastic, organic (food waste), other | *Designates type of waste accepted or dumped at a waste site* |
|  fee | yes, no | *Designates if a fee is necessary to use the waste site* |
|  provider | <name of provider> | *Name of provider, IF different from operator (organization or company responsible for providing operator with waste bins, trash cans, etc.)* |
|  name | <name of waste facility> | *If waste facility has a name* |
|  operator | <name of operator of facility> | *Name of operator (organization or company responsible for collection)* |

**2. Recycling Sites** <br>

|  Key | Value | Description/notes |
| --- | --- | --- |
|  amenity | recycling | *Used for facilities that accept waste for recycling* |
|  recycling_type | container, centre | *Used to differentiate between large recycling service centers and simple recycling containers* |
|  recycling:* | yes,no | *Allows for specific details on what materials are accepted for recycling. See examples below.* |
|  recycling:aluminum | yes,no | *Example of recycling:* tag designating whether or not a recycling site accepts a particular material type.* |
|  recycling:glass | yes,no | *Example of recycling:* tag designating whether or not a recycling site accepts a particular material type.* |
|  recycling:hazardous_waste | yes,no | *Example of recycling:* tag designating whether or not a recycling site accepts a particular material type.* |

**3. Food distribution sites** <br>

See [Goal 2 - Zero Hunger](https://hotosm.github.io/gpsdd-documentation/pages/part-iv-using-open-data-and-maps-to-meet-and-monitor-sdgs/sdg-goal-2/)
