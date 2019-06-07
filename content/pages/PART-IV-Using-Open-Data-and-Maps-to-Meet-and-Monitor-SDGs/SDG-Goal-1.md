---
title: Goal 1 - No Poverty
weight: 1
---

## End poverty in all its forms everywhere

_“Extreme poverty rates have fallen by more than half since 1990. While this is a remarkable achievement, one-in-five people in developing regions still live on less than $1.90 a day. Millions more make little more than this daily amount and are at risk of slipping back into extreme poverty.”_

![](/images/part-iv/market_view.jpeg)

Poverty elimination projects to map low income (often slum) areas can support humanitarian and development programming. Particularly, mapping access to financial services and monitoring areas with low employment rates is fundamental to enabling those living in poverty to become more economically stable and to improve employability and education initiatives. 

Additionally, while property boundaries are not imported into OpenStreetMap directly, putting villages and household footprints on a map is often the first step in giving communities a voice in land rights. “Geospatial information is critical in helping people claim their property rights. OSM allows for a flexible database schema and detailed historical information on how and when data originated. Both of these traits are particularly helpful in property rights, which are essentially a social contract between people about their land (versus solely between a person and the land they inhabit without accounting for their neighbors, community, society, etc.).”[1] 


#### What has been done? 

**[Mapping Financial Inclusion in Uganda:](https://www.hotosm.org/projects/mapping_financial_inclusion_in_uganda)** In order to increase digital financial inclusion, HOT mapped access to financial services in Uganda, allowing providers to analyze gaps in coverage. Access to digital financial services is fundamental to enabling struggling people to become more economically stable, prosperous, and resilient. These services – payments, credit, savings and insurance offered through mobile phones or other technology – are reaching millions of people around the world who had not previously been included in the financial system.

**[Map Kibera:](https://www.hotosm.org/projects/map-kibera-slum-mapping)** The World Bank has partnered with Map Kibera to aid regional counties to engage citizens in an ongoing participatory budgeting process for development initiatives. The main purpose of this project is to use citizen-generated data to ensure that development projects within the counties meet the needs of the people.   


#### What else could be mapped? 



*   Mapping basic services including education, water points, sanitation, and electricity. See Goals 4, 6, and 7 respectively, for examples and data models. 
*   Work with communities and governments to add collectively agreed upon administrative boundaries to the map. 
*   Work with rural communities to map underrepresented villages. 
*   Map commercial activity to understand economic needs and opportunities. 
*   Survey households for land ownership status.


#### OSM Data Model


<table>
  <tr>
   <td>Type
   </td>
   <td>Category
   </td>
   <td>Key
   </td>
   <td>Value
   </td>
   <td>Description/notes
   </td>
  </tr>
  <tr>
   <td rowspan="9" >Commercial activity
   </td>
   <td rowspan="3" >All commercial points of interest
   </td>
   <td>name
   </td>
   <td><Business name; name of the agent location (one can own multiple)>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>noname
   </td>
   <td><em>if no name <yes></em>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>opening_hours
   </td>
   <td>Example: “Mo-Su 08:00-22:00”, “24/7”, “Mo-Fr 08:30-20:00; Sa,Su 08:00-15:00”
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td rowspan="2" >Financial Services / Mobile Money
   </td>
   <td>amenity
   </td>
   <td>mobile_money_agent, bank, banking_agent, atm, credit_institution, microfinance_bank, microfinance, sacco, bureau_de_change, money_transfer
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>network
   </td>
   <td>Airtel Money, Africell Money, MTN Mobile Money, UTL M-Sente, SMART Mobile Money, Vodacom M-Pesa, Safaricom M-Pesa
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td rowspan="2" >Businesses
   </td>
   <td>amenity
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>shop
   </td>
   <td>alcohol, art, bakery, beauty, beverages, bicycle, books, butcher, car, car_parts, car_repair,charcoal, chemist, clothes, convenience, copyshop, cosmetics, electronics, food, furniture, greengrocer, hairdresser, houseware, jewelry, kiosk, mobile_phone, pastry, shoes, stationary, supermarket, tailor, yes
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td rowspan="2" >Markets
   </td>
   <td>amenity
   </td>
   <td>marketplace
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>marketplace:type
   </td>
   <td><agricultural, clothes,mixed>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td rowspan="8" >Boundaries and places
   </td>
   <td rowspan="4" >Administrative boundaries
   </td>
   <td>boundary
   </td>
   <td>administrative
   </td>
   <td>Designates an area as an administrative area
   </td>
  </tr>
  <tr>
   <td>admin_level
   </td>
   <td><1 to 10>
   </td>
   <td><a href="https://wiki.openstreetmap.org/wiki/Tag:boundary%3Dadministrative#10_admin_level_values_for_specific_countries">Indicates the level of an administrative boundary according to country specific guides</a>
   </td>
  </tr>
  <tr>
   <td>addr:*
   </td>
   <td><name of administrative area>
   </td>
   <td>addr: to be followed by the administrative designation (i.e. addr:district, addr:village)
   </td>
  </tr>
  <tr>
   <td>name
   </td>
   <td><name of administrative area>
   </td>
   <td><em>Official or most commonly used name of administrative area</em>
   </td>
  </tr>
  <tr>
   <td rowspan="4" >Places (Villages, towns, cities)
   </td>
   <td>place
   </td>
   <td>city, suburb, town, village, hamlet, <other>
   </td>
   <td><em>Place type, generally based on population size</em>
   </td>
  </tr>
  <tr>
   <td>name
   </td>
   <td><name of the place>
   </td>
   <td><em>Official or most commonly used name of the place</em>
   </td>
  </tr>
  <tr>
   <td>alt_name
   </td>
   <td><if alternative place name>
   </td>
   <td><em>Unofficial or secondary name of the place</em>
   </td>
  </tr>
  <tr>
   <td>population
   </td>
   <td><number>
   </td>
   <td>Official or estimated population size
   </td>
  </tr>
</table>

****
[1] Omidyar Network: https://www.omidyar.com/blog/how-map-can-change-world-state-map-us-2015-conference-emphasizes-role-geospatial-data-property
