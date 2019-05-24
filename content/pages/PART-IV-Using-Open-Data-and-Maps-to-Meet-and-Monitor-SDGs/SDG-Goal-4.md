---
title: Goal 4 - Quality Education
weight: 4
---

## Ensure inclusive and quality education for all and promote lifelong learning 

_“Basic literacy skills across the world have improved tremendously, yet bolder efforts are needed to achieve universal education goals for all. For example, the world has achieved equality in primary education between girls and boys, but few countries have achieved that target at all levels of education.”_

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

**Educational Facilities**


<table>
  <tr>
   <td>Key
   </td>
   <td>Value
   </td>
   <td>Description/notes
   </td>
  </tr>
  <tr>
   <td>amenity
   </td>
   <td>school, kindergarten, college, university
   </td>
   <td><em>Type of school</em>
   </td>
  </tr>
  <tr>
   <td>name
   </td>
   <td><free text>
   </td>
   <td><em>Name of school</em>
   </td>
  </tr>
  <tr>
   <td>operator
   </td>
   <td><free text>
   </td>
   <td><em>Name of operator, often the local education authority</em>
   </td>
  </tr>
  <tr>
   <td>operator:type
   </td>
   <td>public, private, religious, ngo
   </td>
   <td><em>Type of operator</em>
   </td>
  </tr>
  <tr>
   <td>addr:full
   </td>
   <td><free text>
   </td>
   <td><em>Full address</em>
<p>
<em>and/or addr:city, addr:district, addr:street, etc.</em>
   </td>
  </tr>
  <tr>
   <td>capacity
   </td>
   <td>yes, no, <number>
   </td>
   <td><em>Total number of students the school can accept (not current</em>
   </td>
  </tr>
  <tr>
   <td><a href="https://wiki.openstreetmap.org/wiki/Key:grades">grades</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>fee
   </td>
   <td>yes, no
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>religion
   </td>
   <td>christian, muslim, buddhist, <other>
   </td>
   <td>If applicable, add denomination=*
   </td>
  </tr>
  <tr>
   <td>min_age
   </td>
   <td><number>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>max_age
   </td>
   <td><number>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>wheelchair
   </td>
   <td>yes, no
   </td>
   <td><em>Wheelchair accessibility</em>
   </td>
  </tr>
  <tr>
   <td>temporary
   </td>
   <td>yes
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>toilets
   </td>
   <td>yes, no
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>toilets:access
   </td>
   <td>public, staff only
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>staff_count:teachers
   </td>
   <td><number>
   </td>
   <td><em>Number of teachers</em>
   </td>
  </tr>
  <tr>
   <td>generator:source
   </td>
   <td>oil, gas, coal, biomass, <other>
   </td>
   <td><em>Power supply (if any) for the school</em>
   </td>
  </tr>
  <tr>
   <td>water_supply
   </td>
   <td>water_well, pipeline, pump, borehole, <other>
   </td>
   <td>
   </td>
  </tr>
</table>


**Related Facilities and Amenities**


<table>
  <tr>
   <td>Category
   </td>
   <td>Key
   </td>
   <td>Value
   </td>
  </tr>
  <tr>
   <td rowspan="2" >Child friendly space
   </td>
   <td>amenity
   </td>
   <td>social_facility
   </td>
  </tr>
  <tr>
   <td>social_facility
   </td>
   <td>outreach
   </td>
  </tr>
  <tr>
   <td rowspan="2" >Recreation
   </td>
   <td>landuse
   </td>
   <td>recreation
   </td>
  </tr>
  <tr>
   <td>leisure
   </td>
   <td>pitch, playground, park
   </td>
  </tr>
  <tr>
   <td>Community centre
   </td>
   <td>amenity
   </td>
   <td>community_centre
   </td>
  </tr>
</table>
