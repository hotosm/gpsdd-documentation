---
title: Goal 15 - Life on Land
weight: 15
---

## Sustainably manage forests, combat desertification, halt and reverse land degradation, halt biodiversity loss

_“Forests cover 30 percent of the Earth’s surface and in addition to providing food security and shelter, forests are key to combating climate change, protecting biodiversity and the homes of the indigenous population. Thirteen million hectares of forests are being lost every year while the persistent degradation of drylands has led to the desertification of 3.6 billion hectares.”_

Environmental mapping projects help monitor change in environmental features such as coastal erosion, wetlands, and local biodiversity to tackle issues such as climate change, flooding and sustainable livelihoods. Understanding land use and change through mapping can help local communities and organizations develop and maintain sustainable practices. 

### What has been done?

**[The Gambia YMCA’s Computer Training Centre and Digital Studio](https://www.hotosm.org/projects/ymca-computer-training-centre-and-digital-studio-yplus-mapping-local-ecotourism/)** is working with the Gambia Tourism Board and the National Environmental Agency to identify ecotourism areas and capture the current state of vegetation and wildlife to stimulate The Gambia’s tourism industry and assist in planning efforts focused on environmental conservation and preservation.

**[YouthMappers and COASTMAP-URABÁ:](https://www.hotosm.org/updates/2017-10-02_microgrants_humanitarian_mapping_of_coastal_wetlands_and_fishing_livelihoods_for)** Last year, mapping groups in Universidad de Antioquia (Medellín, Colombia) recently joined efforts with an aim to provide an open-source map of the coastal zone of Turbo municipality. The main goal was to put on the map the fishing communities scattered along the coastline. An area of particular interest is El Uno Bay, a peri-urban fishing village severely affected by La Niña 2010-2011. In addition, the group aimed to map mangroves and freshwater wetlands within the area because they are important ecosystems for subsistence of coastal livelihoods. The ultimate objective of COASTMAP-URABÁ is to highlight that coastal wetlands are fundamental elements for the resilience of both fishing livelihoods and the entire coastal zone.

### What else can be mapped? 



*   Adding boundaries of designated protected areas to OpenStreetMap
*   Mapping buildings and infrastructure in and around designated protected areas to understand and monitor encroachment
*   Mapping wetlands and coastlines to understand erosion and impacts of climate change.
*   Mapping land use areas to understand change and development

### OSM Data Model


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
   <td rowspan="4" >Protected Area Boundaries
   </td>
   <td>boundary
   </td>
   <td>protected_area
   </td>
   <td>Designates boundary for protected area
   </td>
  </tr>
  <tr>
   <td>protect_class
   </td>
   <td><protection class number>
   </td>
   <td>Protection level as defined by country https://wiki.openstreetmap.org/wiki/Tag:boundary%3Dprotected_area#Protect_classes_for_various_countries
   </td>
  </tr>
  <tr>
   <td>protection_title
   </td>
   <td><protection title>
   </td>
   <td><em>Title or type of protection, not the name of the protected area</em>
   </td>
  </tr>
  <tr>
   <td>name
   </td>
   <td><protection area name>
   </td>
   <td><em>Name of the protected area</em>
   </td>
  </tr>
  <tr>
   <td rowspan="6" >Landuse
   </td>
   <td>landuse
   </td>
   <td>allotments, farmland, forest, meadow, orchard, plant_nursery, vineyard, basin, brownfield, commercial, construction, depot, residential, industrial, railway, retail, salt_pond, landfill, quarry, reservoir
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>man_made
   </td>
   <td>wastewater_plant, reservoir_covered,
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>leisure
   </td>
   <td>nature_preserve, park
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>natural
   </td>
   <td>water, grassland, wetland, glacier, beach, reef, wood, scrub, heath
   </td>
   <td>Used to describe natural physical land features
   </td>
  </tr>
  <tr>
   <td>wetland
   </td>
   <td>wet_meadow, bog, fen, marsh, swamp, tidal flat <other>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>name
   </td>
   <td><name>
   </td>
   <td>Used to describe natural area subject to inundation or with waterlogged ground
   </td>
  </tr>
  <tr>
   <td rowspan="5" >Waterways
   </td>
   <td>waterway
   </td>
   <td>river, riverbank, stream, canal, drain, ditch, dam
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>name
   </td>
   <td><name>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>intermittent
   </td>
   <td>yes
   </td>
   <td>Indicates that the waterway is usually dry, even during the wet season.
   </td>
  </tr>
  <tr>
   <td>seasonal
   </td>
   <td>yes, spring, summer, autumn, winter, wet_season, dry_season
   </td>
   <td>Indicates that the waterway has a seasonal flow
   </td>
  </tr>
  <tr>
   <td>destination
   </td>
   <td><name>
   </td>
   <td>name of body of water the feature flows into
   </td>
  </tr>
  <tr>
   <td>Monitoring
   </td>
   <td>man_made
   </td>
   <td>monitoring_station
   </td>
   <td>
   </td>
  </tr>
</table>
