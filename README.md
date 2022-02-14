# Yandex_property
Determining the market value of real estate in St. Petersburg and its surroundings

Yandex.Property investigation

The data of the Yandex.Property service is available. Real estate - archive of ads for the sale of apartments in St. Petersburg and neighboring settlements for several years. It is necessary to determine the market value of real estate. 
The main task is to establish the parameters that determine the market value of real estate in St. Petersburg and its surroundings. This will allow us to build an automated system: it will track anomalies and fraudulent activity.
Two types of data are available for each apartment for sale. The first ones are entered by the user, the second ones are obtained automatically based on cartographic data. For example, the distance to the center, the airport, the nearest park and reservoir.

Data description
•	airports_nearest — distance to the nearest airport in meters (m)
•	balcony — number of balconies
•	ceiling_height — ceiling height
•	cityCenters_nearest - distance to the city center (m)
•	days_exposition — how many days the ad was placed (from publication to removal)
•	first_day_exposition — date of publication
•	floor - floor
•	floors_total — total floors in the house
•	is_apartment - apartments (boolean type)
•	kitchen_area — kitchen area in square meters (m2)
•	last_price - price at the time of withdrawal from publication
•	living_area — living area in square meters (m2)
•	locality_name — name of the locality
•	open_plan - free layout (boolean type)
•	parks_around3000 — number of parks within a 3 km radius
•	parks_nearest — distance to the nearest park (m)
•	ponds_around3000 — number of reservoirs within a radius of 3 km
•	ponds_nearest — distance to the nearest reservoir (m)
•	rooms — number of rooms
•	studio - studio apartment (boolean type)
•	total_area — the area of the apartment in square meters (m2)
•	total_images — the number of photos of the apartment in the ad
