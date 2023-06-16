# ETL_Project

# Introduction
This project was carried out in January 2023. It was a group project for the Master's program at Assembler Institute of Technology, and the group members were:
- Lien Chin
- Helen Navarro
- Sergio Salvador
- Rubén Tenreiro
We have chosen to develop each point of the project in phases: Extraction, Standardization, and Trusted. We started with the Extraction phase for each point, followed by the Standardization phase for each point, and finally the Trusted phase for transformation.

# Extraction Phase
The sources used in the Extraction phase are:
- CSV provided in the assignment (Postal Codes.csv).
- INE Source:
To obtain the required data for exercise number 2, we made a GET request to the INE webpage.
- Gob España Source:
To obtain the required data for exercise number 3, we searched for a dataset containing all the required information. We found a census dataset on the INE webpage and used the downloaded data in CSV format.

After reading the documentation and testing different APIs on the Spanish government website, we decided to find a simpler way to obtain the required information, as suggested in the assignment by "Finding a way." All files are saved in the RAW folder in CSV format.

# Standardization Phase
In the Standardization phase, we saved the structured DataFrames in CSV format (Postal_Codes, Girona, and Census_Data). All the structured files are automatically saved in the STANDARISED folder.

# Trusted Data Phase
In the Trusted phase, we saved the transformed and fully cleaned data in Excel files (postal_codes_trusted, girona_trusted, and census_data_trusted) in the TRUSTED folder.

# Conclusion
We have learned that there are several ways to approach this exercise. Out of the two options available to us, we chose to create a datalake where we stored all the sources in the same folder called RAW. Then, we standardized the data so that each piece of information is in its corresponding column or field and saved it in a folder called Standardized. The last phase involved cleaning all the data from each source (formatting, removing nulls, etc.) and saving the output in an Excel file, as required, in a folder called Trusted. These data are ready to be used.

We researched alternative ways to obtain the requested data, using Google searches and later referring to the INE.

We reviewed pandas code and, among our team members, we provided solutions and learned from each other's code.
