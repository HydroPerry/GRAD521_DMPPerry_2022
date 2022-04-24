# GRAD521_DMPPerry_2022
Data Management Plan for Z. Perry's Graduate Research Project

Context of the Project:
1.	We are trying to better understand the physics that drives the hydrologic response of a catchment to precipitation inputs. The response depends not only on the inputs (rain and snow), but also the way the water moves and mixes on and below the surface. This is largely driven by the physiography (geology, geomorphology, and topography). We will use water stable isotopes as a tracer to estimate water transit time and storage. We will then utilize lidar derived metrics of physiography to identify metrics that relate to our understanding of transit time and storage potential – things like slope, roughness, or bedrock type. LiDAR is a form of active remote sensing that allows us to map an area with a fine spatial resolution (<1m) utilizing a system that sends out a laser, and then receives the same beam back. It measures the distance between the unit and the object being scanned by analyzing the time it took the beam to return to the unit. The overall goal of this work is to be able to predict event transit times and storage in ungauged locations after storm events. Our work will focus on headwater systems in the Cascade Mountains, as headwaters are indicative of water quality and quantity for downstream users. This work has the potential to make water predictions easier for those working with ungauged basins. 
2.	The datasets I will utilize are:
a.	Isotopic composition of water samples collected from streams in the HJ Andrews Forest. This data will include values for δ18O and δ2H for each sample and will correspond to GPS coordinates collected during the time of the sample collection. This data exists in excel spreadsheets, and will be gathered across seasons and locations within the forest. In addition to isotopic composition for stream water samples, the same data will exist for rain water samples collected throughout the year. The isotopic data will be generated using a Picarro Spectrometer. 
b.	LIDAR point cloud data will be utilized to measure physiographic features of the catchments I am collecting samples from. This data will exist as point cloud data (.las) and also as DEMs that will be analyzed in ArcGIS. This data is from a 2011 aerial lidar scan of the HJ Andrews Forest. The .las files will be analyzed using a software called Rambo (developed by Michael Olsen and Erzhuo Che at OSU).
c.	Hydrometric data collected by the Andrews Forest team as a part of the LTER work that has been going on since the 1950s. This data will primarily be stream discharge, precipitation amounts (snow and rain), temperature, and other atmospheric data required by the hydrologic model I decide to use. I have not done much work on this part of the project yet, as it will not be applicable until I finish creating an isotopic profile. All data required will come from the HJ Andrews website, where they maintain a database of collected attributes. This will exist as excel files. The results of the model will be simulated discharge data and residence time, and will also exist as excel files. 
3.	The sizes of the datasets will be:
a.	1-5GB
b.	10-100 GB
c.	1-10GB
