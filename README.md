## Solar Data Discovery

## Introduction
This week we worked on analyzing data from Solar Radiation Measurement to help our client, MoonLight Energy Solutions. We tried to identify key trends and gain some insight from the data to help our client make strategic decisions about solar investment. Specifically, we focused on three countries, Benin, Togo, and Sierra Leone to identify the region with the highest potential for solar installation. 

## Methodology

**Understanding the problem**  
The data we have has measurements about the solar radiation reaching the Earth’s surface. It is collected via sensors on the ground and it is essential to deploy the right solar applications. While temperature, humidity, and wind influence solar system performance, DHI, DNI, and GHI are the foundational parameters as they enable optimal system sizing, tech selection, and energy selection. So we will prioritize these parameters in our analysis. 
Global Horizontal Irradiance (GHI) – combines direct and diffuse sunlight to estimate energy output for photovoltaic systems. 
Direct Normal Irradiance (DNI) – measures direct sunlight received on the perpendicular surface
Diffuse Horizontal Irradiance (DHI) – measures scattered sunlight and how solar energy is available on cloudy days to contribute to total energy captured by photovoltaic.

**Setting up the environment**  
We started with preparing the repository for our project with the necessary branches.

**Cleaning the data** 

We had the data from the countries. Each data set contained important parameters that would help us with the analysis. To clean this data, we looked for missing values and outliers and proceeded to impute these values. We specifically used the Z-scores to identify the outliers and replaced them with the median of the column.

**Exploring the data** 

To understand the data better, graphs were drawn. They showed the monthly and daily variation in parameters such as GHI, DNI, and DHI. Heat maps of the correlation matrix between different values were drawn. Additionally, wind distribution analysis and temperature analysis were done to gain better insight to the other parameters that affect solar potential.
 

**Comparing the countries** 
After the data was cleaned, we proceeded to compare the three countries to find the one with the highest solar potential. We drew boxplots of GHI, GNI, and DHI of each country to find which has the best parameters. We also prepared a summary table to summarize our findings.

## Result

After analyzing the data we found the following results. 
•	Benin has the highest average GHI and DNI while the three countries have similar values of DHI.
•	Sierra Leone has the lowest variations in GHI and DNI values while Benin has the highest.
•	The DHI values of each country has similar variations.
 
                     

## Challenges
•	Limited information about how the data was collected – There were negative values for GHI, DNI, and DHI. Based on the definitions, these values are generally positive but can be negative depending on the instrument used and the situation at the time of data collection. More knowledge about the instrument used would have helped in categorizing these values as genuine entries or instrument errors.

•	One of the major challenges was finding a notebook library version that is compatible with the python version that was installed on my system. 


## Conclusion 
This was an eye-opening project. Not only did we get to practice new technical skills such as version control and github, we also got to see what end-to-end project deployment looks like. We assessed three countries to understand their potential and choose the one that aligns well with our client’s goals. The client can use the results of our analysis to make an informed decision. Above anything, this project taught me to step my time management game up when learning new concepts. I learned to prioritize and focus on high-yield tasks.  
