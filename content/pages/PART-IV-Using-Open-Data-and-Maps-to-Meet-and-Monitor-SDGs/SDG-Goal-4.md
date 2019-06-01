---
title: Goal 4 - Quality Education
weight: 4
---

## Ensure inclusive and quality education for all and promote lifelong learning 

_“Basic literacy skills across the world have improved tremendously, yet bolder efforts are needed to achieve universal education goals for all. For example, the world has achieved equality in primary education between girls and boys, but few countries have achieved that target at all levels of education.”_

![](/images/part-iv/Unknown-2.jpg)

Open mapping provides a two-fold benefit towards reaching the SDG for education: assisting partners, governments, and local communities understand gaps in services and distribution of educational facilities, as well as providing an opportunity for individuals in these groups to gain technical and vocational skills such as GIS and surveying.  

### What has been done? 

**[GAL (Peru):](https://www.hotosm.org/updates/mapping-sexist-publicity/)** HOT local partner GAL School Peru is training local high school students in Cusco to identify under-represented social issues, and then investigate, map and share them. To date, groups of school girls in Cusco have created campaigns that use maps of sexist publicity and behaviour, presenting them as part of an international festival and to local government representatives, as well as peers and the broader school community. 

**[Crowdsourcing Non-Camp Refugee Data Through OpenStreetMap:](https://www.hotosm.org/projects/urban_innovations_crowdsourcing_non-camp_refugee_data)** In northern Uganda, refugees and host community members were trained and provided with the tools to map vulnerabilities and assets in their communities, including educational facilities. This educational data, combined with other features mapped, allowed for analysis and map creation showing patterns such as distance refugees and host community members need to walk to school and the distance between educational facilities and the closest safe drinking water points. Through this project, HOT also provided training to secondary school students and teachers in the refugee-hosting district of Arua covering subjects such as how to use OpenStreetMap to navigate, how to read a map, and how teachers can use OSM during geography lessons. 

### What else can be done?


*   Provide vocational training in the latest open source GIS tools to substantially increase the number of youth and adults who have relevant skills, including technical and vocational skills, for employment, decent jobs, and entrepreneurship. 
*   Map barriers to education, such as the distance students must travel to school and unsafe or vulnerable areas en route to or near schools. 
*   Create detailed maps of schools in a given community, along with information about school size, number of teachers, number of bathrooms available, etc., to empower parents when they choose a school for their children. 
*   Engage students in on-the-ground geographic data collection to improve map literacy and spatial awareness, as well as empower students to have a say in how their community is represented on the world map. 

### OSM Data Model

**1. Minimum educational facility tagging** <br>

|  Key | Value | Description/notes |
| --- | --- | --- |
|  amenity | school, kindergarten, college, university | *Type of school* |
|  name | <free text> | *Name of school* |
  
**2. Additional educational facility tagging** <br>

|  Key | Value | Description/notes |
| --- | --- | --- |
|  operator | <free text> | *Name of operator, often the local education authority* |
|  operator:type | public, private, religious, ngo | *Type of operator* |
|  addr:full | <free text> | *Full address<br/>and/or addr:city, addr:district, addr:street, etc.* |
|  capacity | yes, no, <number> | *Total number of students the school can accept (not current* |
|  grades | <grade number range> | *Grades serviced at school* |
|  fee | yes, no | *Requirement of students to pay fee to attend* |
|  religion | christian, muslim, buddhist, <other> | *If applicable, add denomination=** |
|  min_age | <number> | *Lowest age of students allowed to enroll* |
|  max_age | <number> | *Highest age of students allowed to enroll* |
|  wheelchair | yes, no | *Wheelchair accessibility* |
|  temporary | yes | *Denotes if school is temporary facility or structure* |
|  toilets | yes, no | *Denotes if school has toilets available* |
|  toilets:access | public, staff only | *Access to available toilets* |
|  staff_count:teachers | <number> | *Number of teachers* |
|  generator:source | oil, gas, coal, biomass, <other> | *Power supply (if any) for the school* |
|  water_supply | water_well, pipeline, pump, borehole, <other> | *Water supply (if any) for the school* |
