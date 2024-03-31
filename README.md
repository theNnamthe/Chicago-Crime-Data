<div style="font-size: 50px;" align='center'> <b>CHICAGO: UNCOVERING THE CRIME </b></div>

#

<!--sup>[1](https://en.wikipedia.org/wiki/Crime_in_Chicago)</sup-->


<div align='center'><img src="https://gisgeography.com/wp-content/uploads/2020/06/Chicago-Road-Map-1000x1294.jpg" alt="Chicago Road Map" width="500" height="auto"></div>

### Description:
This Analysis aims to use the dataset to uncover patterns, trends, knowledge about crime in Chicago, the most populous city in Illinois state of the United State of America

# 

### An explanation of features in the Chicago crime dataset:
- ID: A unique identifier for each crime incident.

- Case Number: A unique identifier for each reported crime case.

- Date: The date and time when the crime incident occurred.

- Block: The block address where the crime incident occurred.

- IUCR: The Illinois Uniform Crime Reporting code, which categorizes the type of crime.

- Primary Type: The primary classification of the crime (e.g., theft, assault, burglary).

- Description: A detailed description of the crime.

- Location Description: Description of the location where the crime incident occurred (e.g., street, residence, store).

- Arrest: Indicates whether an arrest was made for the crime (TRUE/FALSE).

- Domestic: Indicates whether the crime incident involved domestic violence (TRUE/FALSE).

- Beat: The police beat where the crime incident occurred (a specific geographic area or patrol zone that is assigned to a police officer or a group of officers for regular patrolling).

- District: The police district where the crime incident occurred (It encompasses multiple police beats and is typically overseen by a higher-ranking officer).

- Ward: The ward where the crime incident occurred (wards represent political and administrative divisions within the city).

- Community Area: The community area where the crime incident occurred.

- FBI Code: A code representing the classification of the crime according to the FBI's Uniform Crime Reporting (UCR) system.

- X Coordinate: The X coordinate of the location where the crime incident occurred (used for mapping).

- Y Coordinate: The Y coordinate of the location where the crime incident occurred (used for mapping).

- Updated On: The date and time when the record was last updated.
 
 - Geographical Location: A combination of Latitude and Longitude, often in the form of (Latitude, Longitude).

Year: Extracted from the Date feature to provide the year of the crime incident.

Month: Extracted from the Date feature to provide the month of the crime incident.

Day of Week: Extracted from the Date feature to provide the day of the week when the crime incident occurred.

Hour: Extracted from the Date feature to provide the hour of the day when the crime incident occurred.

Season: Derived from the month to indicate the season (e.g., winter, spring, summer, fall) when the crime incident occurred.

Weekend: Binary indicator (TRUE/FALSE) to denote whether the crime incident occurred on a weekend (Saturday or Sunday).

Time of Day: Categorization of the hour feature into distinct time periods (e.g., morning, afternoon, evening, night).

Distance from City Center: Calculated distance from the city center or a reference point to provide spatial context to the crime incidents.

Weather Conditions: Information about weather conditions (e.g., temperature, precipitation) at the time of the crime incident, if available.

Neighborhood Socioeconomic Status: Indicators of the socioeconomic status of the neighborhood where the crime incident occurred (e.g., median income, education level).

Population Density: Population density of the area where the crime incident occurred, which may influence crime rates.

Proximity to Public Transit: Distance or accessibility to public transportation hubs, which may impact crime patterns.

Presence of CCTV Cameras: Information on the presence or density of CCTV cameras in the vicinity of the crime incident.

Type of Weapon Used (if applicable): Additional information on the type of weapon used in the commission of the crime, if available.


Crime Committed Most by Each Gender: This feature could involve analyzing the dataset to determine the most common types of crimes committed by individuals of different genders. For example, you could create separate counts for male and female offenders for each type of crime and identify the most frequent crime for each gender.

Gender that Commits Most Crime: This feature could provide an overall comparison of crime rates between genders, indicating which gender is associated with a higher number of reported crimes in the dataset.

Gender that Commits Less Crime: Similar to the previous feature, this could indicate which gender is associated with a lower number of reported crimes in the dataset.

Crime with the Highest Penalty: Identify the type of crime that typically carries the highest penalties or sentences upon conviction. This could involve analyzing the severity of offenses based on legal statutes or guidelines.

Less Pardonable Crime: Identify crimes that are generally considered less pardonable or eligible for leniency or forgiveness. This could involve examining factors such as public perception, legal considerations, and societal norms.

Crime Committed Against a Family: Create a category or flag for crimes that specifically involve victims who are family members or crimes that occur within a family context (e.g., domestic violence, child abuse).

Crime Committed by Groups: Identify crimes that are commonly perpetrated by organized groups or gangs. This could involve analyzing patterns of criminal behavior involving multiple offenders or coordinated criminal activities.

#

### Hierarchy of Location (Broad to Specific)
- State
- City
- District
- Ward
- Community Area
- Street
- Block
- Latitude and Longitude

#

### Dataset Year Range
2001 - 2022


#

### Observation
- Gender is advised to be included in future data collection


#


### Dataset Source
[Chicago Data Portal](https://data.cityofchicago.org/)