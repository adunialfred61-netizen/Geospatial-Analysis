🗺️ University of Ghana Main Campus Mapping Project
Author: Aduni Alfred Awoja
Project Type: GIS Mapping & Spatial Data Visualization
Tools Used: Handy GPS, Microsoft Excel, QGIS, OpenStreetMap

📘 Overview
This project focuses on the creation of a detailed map of the University of Ghana Main Campus using field-collected GPS data and QGIS. The purpose was to help new students, visitors, and researchers navigate the campus easily through an accurate and visually clear digital map.
The map captures the main features within the campus — including buildings, parks, roads, pitches, and car parks — and was designed entirely from raw GPS data collected during fieldwork.

🎯 Objectives
•	Collect geographic coordinates of key features on the University of Ghana campus using a handheld GPS.
•	Organize field data in Excel and export as CSV for GIS processing.
•	Import and digitize data within QGIS, replacing OpenStreetMap base layers with custom vector layers.
•	Produce a user-friendly and publishable campus map complete with legend, title, and scale.
•	Provide a navigation aid for new students and visitors.

🧭 Methodology
1. Field Data Collection
Coordinates were captured around the University of Ghana’s main campus using a handy GPS device.
Points were taken for features such as:
•	Buildings
•	Roads and footpaths
•	Car parks
•	Parks and pitches
The coordinates were recorded in a field notebook for data entry.

2. Data Preparation
•	The GPS coordinates were entered into Microsoft Excel and organized into columns (Name, Latitude, Longitude, Feature Type).
•	The Excel sheet was saved as a CSV file for easy import into QGIS.

3. Data Processing in QGIS
1.	Imported the CSV dataset into QGIS.
2.	Displayed the points using their coordinate reference system (CRS).
3.	Used OpenStreetMap as a temporary basemap to guide digitization of:
o	Roads
o	Buildings
o	Parks and pitches
o	Car parks and pathways
4.	Removed the OpenStreetMap layer after digitization.
5.	Styled each layer:
o	Buildings → red polygons
o	Roads → grey lines
o	Footpaths → dashed lines
o	Parks & pitches → green polygons

4. Map Design
•	Added legend, scale bar, north arrow, and title ("UNIVERSITY OF GHANA: MAIN CAMPUS").
•	Adjusted layout for professional presentation.
•	Included author credit and fieldwork note (“Filed Work 3–5 Final Edit”).

🧩 Results
The final output is a digitized and accurate map of the University of Ghana Main Campus, designed for:
•	Ease of navigation for new students and visitors.
•	Spatial understanding of the university’s infrastructure.
•	Future GIS updates and research applications.
The project highlights how GPS and QGIS can work together to produce high-quality spatial data products from scratch.

💡 Key Insights
•	Field GPS data provides more accuracy than relying solely on web-based maps.
•	Digitizing from OSM ensures spatial precision while allowing for custom styling.
•	GIS tools like QGIS make it possible to visualize and manage spatial data in ways that support navigation and campus planning.

🔍 Recommendations
•	Integrate the final map into a web-based interactive GIS for real-time navigation.
•	Periodically update the dataset to reflect new buildings or road changes.
•	Include attribute data (e.g., department names, offices) for more informative use.
•	Extend this workflow to other campuses or institutions.

🗂️ Project Files
File	Description
university_of_ghana_map.qgz	QGIS project file
	
coordinates.csv	Raw GPS coordinates collected from fieldwork
map_of_university_of_ghana.png	Final map layout (digitized version)
README.md	Project documentation (this file)
 The coordinates.csv  is not yet available because I lost the pendrive that I had the file in.
🧠 Skills Demonstrated
•	Field data collection using GPS
•	Data organization and transformation (Excel → CSV → QGIS)
•	Spatial data visualization and map design
•	GIS analysis and cartographic layout
•	Geospatial communication and project documentation

🗺️ Preview

🏁 Conclusion
This project demonstrates how practical GIS and GPS applications can support spatial decision-making, planning, and navigation within a university environment. The final map stands as both a navigation tool and a technical proof of concept for applying GIS to real-world campus mapping.

