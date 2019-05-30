---
title: Goal 3 - Good Health and Wellbeing
weight: 3
---

## Ensure healthy lives and promote well-being for all at all ages

“Significant strides have been made in increasing life expectancy and reducing some of the common killers responsible for child and maternal mortality. Major progress has also been made on increasing access to clean water and sanitation, reducing malaria, tuberculosis, polio and the spread of HIV/AIDS. However, many more efforts are needed to control a wide range of diseases and address many different persistent and emerging health issues.”

![](/images/part-iv/map-boy.jpg)

Public health data collection projects provide local governments and organizations with the information to improve their response to health-related issues, such as malaria prevention, and cholera and Ebola outbreaks. Adding health facilities and their capacities to OpenStreetMap can help governments and partners understand gaps in services, help local communities locate nearest services, and assist first responders when disease outbreaks occur. Understanding household information and distribution can also assist with improving access to health care and monitoring behavior that impacts health outcomes. 


#### What has been done?  

**[Data Zetu:](http://datazetu.dlab.or.tz/)** In Tanzania, HOT used mapping data they had collected on wards, sub-wards and districts in Dar es Salaam – corroborated by local communities on the ground – to provide Amana Hospital with information to better pinpoint patients’ geographic origin. With this information, the hospital can identify locations that are at risk of diseases, enabling them to prevent infection and even fight infant malnutrition. After updating the hospital’s electronic systems, HOT also trained 40 staff at the hospital on how to use the data.

**[Malaria Elimination:](https://www.hotosm.org/updates/field-surveying-in-botswana-to-support-the-national-malaria-programme/)** In 2018, HOT supported malaria elimination projects on the ground in Guatemala and Botswana by providing geographical data and training to national governments. These projects worked to improve the usefulness of the OSM data in malaria elimination interventions, including support for the logistics and indoor residual spraying campaigns, better data for further types of interventions such as bed net distribution, and improved monitoring and evaluation to measure intervention impacts. 


#### What else could be mapped?



*   Map areas affected by disease outbreaks to more effectively track new cases and transmission on the ground, aimed at ending the epidemics of AIDS, tuberculosis, malaria, and neglected tropical diseases. 
*   Map incidence of households displaying healthy behaviors; for example, sleeping under a long-lasting insecticide-treated bednet in malarious countries or seeking timely care when ill. 
*   Map barriers to healthcare services, such as the distance people must travel for healthcare and the cost of transportation. 
*   Map spaces that are accessible or inaccessible to people with disabilities. 


#### OSM Data Model 


<table>
  <tr>
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
   <td rowspan="20" >Health facilities
   </td>
   <td>amenity
   </td>
   <td>clinic, doctors, hospital, dentist, pharmacy
   </td>
   <td>For describing useful and important facilities for visitors and residents
   </td>
  </tr>
  <tr>
   <td>healthcare
   </td>
   <td>doctor, pharmacy, hospital, clinic, dentist, physiotherapist, alternative, laboratory, optometrist, rehabilitation, blood_donation, birthing_center
   </td>
   <td>A key to tag all places that provide healthcare (are part of the healthcare sector)
   </td>
  </tr>
  <tr>
   <td>healthcare:speciality
   </td>
   <td>* these values are options available when the healthcare=laboratory tag is applied to a health facility (biology, blood_check, clinical_pathology, diagnostic_radiology, medical_physics, medical_engineering, radiology)
   </td>
   <td><em>A key to detail the special services provided by a healthcare facility. To be used in conjuction with the 'healthcare=*' tag. For example 'healthcare=laboratory', and 'healthcare:speciality=blood_check'</em>
   </td>
  </tr>
  <tr>
   <td>name
   </td>
   <td><name of health facility>
   </td>
   <td><em>The primary tag used for naming an element</em>
   </td>
  </tr>
  <tr>
   <td>operator
   </td>
   <td><name of operator>
   </td>
   <td>The operator tag is used to name a company, corporation, person or any other entity who is directly in charge of the current operation of a map object
   </td>
  </tr>
  <tr>
   <td>operator:type
   </td>
   <td>public, private, community, religious, government, ngo, combination
   </td>
   <td>This tag is used to give more information about the type of operator for a feature
   </td>
  </tr>
  <tr>
   <td>addr:full
   </td>
   <td><full address>
   </td>
   <td>Used for a full-text, often multi-line, address for buildings and facilities
   </td>
  </tr>
  <tr>
   <td>contact:phone
   </td>
   <td><phone number>
   </td>
   <td>The contact tag is the prefix for several contact:* keys to describe contacts
   </td>
  </tr>
  <tr>
   <td>operational_status
   </td>
   <td>operational, non_operational, unknown
   </td>
   <td>Used to document an observation of the current functional status of a mapped feature
   </td>
  </tr>
  <tr>
   <td>opening_hours
   </td>
   <td><days/times of opening>
   </td>
   <td>Describes when something is open or closed. There is a specific standard format for this data https://wiki.openstreetmap.org/wiki/Key:opening_hours/specification
   </td>
  </tr>
  <tr>
   <td>beds
   </td>
   <td><number of beds>
   </td>
   <td><em>Indicates the number of beds in a hotel or hospital</em>
   </td>
  </tr>
  <tr>
   <td>staff_count:doctors
   </td>
   <td><number of doctors>
   </td>
   <td><em>Indicates the number of doctors in a hospital</em>
   </td>
  </tr>
  <tr>
   <td>staff_count:nurses
   </td>
   <td><number of nurses>
   </td>
   <td>Indicates the number of nurses in a hospital
   </td>
  </tr>
  <tr>
   <td>health_amenity:type
   </td>
   <td>ultrasound, mri, x_ray, dialysis, operating_theater, laboratory, imaging_equipment, intensive_care_unit, emergency_department
   </td>
   <td>Indicates what type of speciality medical equipment is available at the healthsite
   </td>
  </tr>
  <tr>
   <td>dispensing
   </td>
   <td>yes, no
   </td>
   <td>Whether a pharmacy dispenses prescription drugs or not. Used to add information to something that is already tagged as amenity=pharmacy
   </td>
  </tr>
  <tr>
   <td>wheelchair
   </td>
   <td>yes, no
   </td>
   <td>Used to mark places or ways that are suitable to be used with a wheelchair and a person with a disability who uses another mobility device (like a walker)
   </td>
  </tr>
  <tr>
   <td>emergency
   </td>
   <td>yes, no
   </td>
   <td>This key describes various emergency services
   </td>
  </tr>
  <tr>
   <td>insurance:health
   </td>
   <td>no, public, private, unknown
   </td>
   <td>This key describes the type of health insurance accepted at the healthsite
   </td>
  </tr>
  <tr>
   <td>water_source
   </td>
   <td>well, water_works, manual_pump, powered_pump, groundwater, rain
   </td>
   <td>Used to indicate the source of the water for features that provide or use water
   </td>
  </tr>
  <tr>
   <td>electricity
   </td>
   <td>grid, generator, solar, other, none
   </td>
   <td>Used to indicate the source of the power generated
   </td>
  </tr>
  <tr>
   <td rowspan="5" >Building Assessments
   </td>
   <td>building
   </td>
   <td>residential, commerical, school, hospital, kitcen, toilets, church, <other>
   </td>
   <td>Indicates the useage(s) of the building.
   </td>
  </tr>
  <tr>
   <td>building:levels
   </td>
   <td><number of levels>
   </td>
   <td>Number of levels in the building
   </td>
  </tr>
  <tr>
   <td>building:material
   </td>
   <td>brick, cement_block, concrete, glass, loam, metal, plaster, reed, wood, mud, canvas, grass, <other>
   </td>
   <td>Material(s) used in wall construction
   </td>
  </tr>
  <tr>
   <td>building:roof
   </td>
   <td>thatch, wood, asphalt, tile, metal, plastic, cement, <other>
   </td>
   <td>Material(s) used in roof construction
   </td>
  </tr>
  <tr>
   <td>wall
   </td>
   <td>yes, no
   </td>
   <td>Indicates whether or not a structure can be considered fully walled (i.e. four walls) or if a stucture is open (i.e. three walls or fewer).
   </td>
  </tr>
</table>
