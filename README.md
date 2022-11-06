# American Society of Agronomy (ASA) 2022 Annual Meeting Workshop

This is a workshop hosted by ASRS (Airborne & Spaceborne Remote Sensing) - led by Jinha Jung (jinha@purdue.edu) and Deepak Joshi (deepak.joshi@sdstate.edu) - and PAS (Precision Agriculture System) - led by Simerjeet Virk (svirk@uga.edu) and Mahendra Bhandari (mahendra.bhandari@ag.tamu.edu) - communities of American Society of Agronomy.

## Leveraging NASA Geospatial Data Products for Agriculture Applications

### Instructors

* Elizabeth Joyner: Community Coordinator at NASA Earth Science Data Systems Programs, Elizabeth.r.joyner@nasa.gov
* Jennifer Wei: NASA Earth Science and Data Information System (ESDIS) Project scientist, jennifer.c.wei@nasa.gov
* Binita KC: NASA Goddard Space Flight Center, Goddard Earth Science Data Information Services Center, binita.kc@nasa.gov
* Zhong Liu: NASA Goddard Space Flight Center, Goddard Earth Science Data Information Services Center, zhong.liu-1@nasa.gov
* Chris Battisto: NASA Goddard Space Flight Center, Goddard Earth Science Data Information Services Center, christopher.m.battisto@nasa.gov
* Ashley Heath: NASA Goddard Space Flight Center, Goddard Earth Science Data Information Services Center, ashley.l.heath@nasa.gov
* Bradley Macpherson: Lead Developer, NASA Langley Research Center, Prediction Of Worldwide Energy Resources (POWER), bradley.macpherson@nasa.gov

### Requirement

* Participants are expected to bring their own laptop.
* Basic understanding of remote sensing is required.
* Participants need to create an account on EarthData (https://urs.earthdata.nasa.gov/users/new).
* Participants need to have a Google account to access a sharable Google Colab notebook.

### Location: 
Hyatt Regency Baltimore Inner Harbor Hotel (300 Light Street), Chesapeake AB room on the 3rd floor.  

### Agenda: Sunday, November 6

| Time          | Title         | Speaker       |
| ------------- | ------------- | ------------- |
| 1:00 - 1:05 PM  | Introductory remarks | Jinha Jung and Simerjeet Virk |
| 1:05 - 1:25 PM  | [NASA Tools for Your Agriculture Applications](01-NASA_Earth_Science_Data_System.md)  | Elizabeth Joyner |
| 1:25 - 1:45 PM  | [Introduction to NASA Science Enabling Center](02-GES_Data_Information_Service_Center.md)  | Jennifer Wei |
| 1:45 - 2:05 PM  | [Introduction to POWER Project](03-POWER.md)  | Bradley Macpherson |
| 2:05 - 2:20 PM  | Break  |  |
| 2:20 - 3:40 PM  | [Hands-on exercise 1](05-Hands_on_exercise.md)  | Jennifer Wei, Zhong Liu, Ashley Heath, Chris Battisto and Binita KC |
| 3:40 - 5:00 PM  | [Hands-on exercise 2 - POWER](06-Hands_on_exercise_2.md)  | Bradley Macpherson |

### Poll 
* Go to www.menti.com
* * Onset of Workshop- Code: 2297 0202
* * Parking Lot for Questions- Code: 15 28 44 2
* * At the End - Code: 3231 7921

### Resources

1. NASA Earth Science Data Systems, https://www.earthdata.nasa.gov/ 
* Agriculture and Water Resources Data Pathfinder, https://www.earthdata.nasa.gov/learn/pathfinders
* All Pathfinders, https://www.earthdata.nasa.gov/learn/pathfinders

2. NASA Applied Sciences Program - Agricultural Activities <https://nasaharvest.org/nasa-agriculture-activities>
      * Applied Remote Sensing Training (ARSET) <https://arset.gsfc.nasa.gov/>
      * Water Resources Program <https://appliedsciences.nasa.gov/programs/water-resources-program>
      * Western Water Applications (WWAO) <https://wwao.jpl.nasa.gov/>
      * SERVIR <https://www.nasa.gov/mission_pages/servir/index.html>
      * VALUABLES (VALUABLES is a collaboration with NASA to measure how satellite information benefits people and the environment when it is used to make decisions.) <https://www.rff.org/valuables/>
      * 2022 Commodity Classic: How Satellite Data Can Help Farmers Capitalize on Regenerative Agriculture <https://youtu.be/Gn7q8XlmYbo>

3. NASA Prediction Of Worldwide Energy Resources (POWER)
     * POWER's Homepage <https://power.larc.nasa.gov/>
     * POWER's Documentation <https://power.larc.nasa.gov/docs/>
     * POWER in AWS Open Data Portal <https://registry.opendata.aws/nasa-power/>

4. NASA Harvest, <https://nasaharvest.org/>

5. NASA Research and Analysis
     * Land Cover Land Use Change Program (LCLUC) <https://lcluc.umd.edu/>
     * Hydrological Sciences <https://science.gsfc.nasa.gov/earth/hydrology/>
     * Terrestrial Ecology <https://cce.nasa.gov/terrestrial_ecology/>

### Questions and Answers: Parking Lot

* What is the status of Open ET? What is the geographical coverage extent?
     [OpenET](https://openetdata.org/) OpenET provides global data at different scales. 
* What national, publicly-available DEM has the highest resolution?
     [OpenDEM](https://www.opendem.info), 30m resolution
* It looked like on the map in the POWER presentation that there’s either no use or no data coming from western US What is the reason for that? The map shows the hits asking for data via the POWER API access. 
* Are there applications that are ready to use by crop consultants etc to make recommendations to farmers? Is there training available in these?
     * NASA's ARSET Training
          * ARSET - [Satellite Remote Sensing for Agricultural Applications](https://appliedsciences.nasa.gov/join-mission/training?program_area=16&languages=All&source=All)
     * Agricultural Data Visualizations/Portal
          * [Agrometeorological (AGMET) Earth Observations (EO) Indicators](https://cropmonitor.org/tools/agmet/) The Agrometeorological (AGMET) Earth Observations (EO) Indicators bring together a variety of Earth Observation (EO) data products on the sub-national scale, each of which provides valuable insights on in-season crop development and current crop conditions. Combined, the different EO data plots help tell the story of in-season crop conditions through the use of different climate, environmental, and vegetative variables
          * [Global Agriculture Monitoring System (GLAM)](https://glam.nasaharvest.org/)The Global Agriculture Monitoring System (GLAM) is a web-based platform to enable near-real-time monitoring of global croplands, primarily using NASA MODIS satellite data. After years of operational use and valuable feedback from partners, it was time to redesign this system to be faster, more flexible, and to capitalize new datasets coming online and new computing architectures available.
          * [OpenET](https://openetdata.org/) OpenET uses best available science to provide easily accessible satellite-based estimates of evapotranspiration (ET) for improved water management across the western United States. Using the Data Explorer, users can explore ET data at the field scale for millions of individual fields or at the original quarter-acre resolution of the satellite data.
          * [Crop Monitor Open](https://cropmonitor.org/index.php/cmreports/amis-report/), timely, and science-driven information on crop conditions in support of market transparency and early warning of production shortfalls.
          * [Crop Condition and Soil Moisture Analytics (Crop-CASMA)](https://nassgeo.csiss.gmu.edu/CropCASMA/)is a web-based geospatial application. It is designed to remotely sense geospatial soil moisture and vegetation index data derived from NASA Soil Moisture Active Passive (SMAP) and Moderate Resolution Imaging Spectroradiometer (MODIS) missions to assess U.S. soil moisture condition and crop vegetation conditions.
          * [CropScape](https://nassgeodata.gmu.edu/CropScape/) CropScape is a geospatial data service, which offers advanced tools such as interactive visualization, web-based data dissemination, geospatial queries, and automated data delivery to systems such as Google Earth. It was developed in cooperation with the Center for Spatial Information Science and Systems at George Mason University.
          * [VegScape](https://nassgeodata.gmu.edu/VegScape/) is a geospatial data service, which offers automated updates of vegetative conditions. It delivers interactive vegetation indices that enable quantification of U.S. crop conditions for exploring, visualizing, querying, and disseminating via interactive maps. It was developed in cooperation with the Center for Spatial Information Science and Systems at George Mason University
          * [CropManage](https://cropmanage.ucanr.edu/) agricultural app	delivers irrigation and fertilizer recommendations to farmers and irrigators. Working with California State University Monterey Bay and the University of California Agriculture and Natural Resources Institute, NASA is linking space-based observations, supercomputing resources and CropManage to reduce barriers to information access and increase uptake of data-driven approaches to scheduling irrigation and fertilizer use.
          * [CroplandCROS](https://croplandcros.scinet.usda.gov/)app to explore, derive and compare agricultural commodities and Cropland Data Layers (CDL) within the continental United States. Estimate acreage by defining an area of interest. Export and download data layers and results. See the CroplandCROS Resources section below for downloadable data and additional information.
* How is POWER different from the Hydrology Data Rods time series? 
     * POWER offers a more limited scope of data parameters, as well as a variety of data visualization tools and an API. The data rods offers many more datasets but no API.
