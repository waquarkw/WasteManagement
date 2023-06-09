# WasteManagement
An analysis of waste management across world using countries recorded/available data.
The idea of this project is to understand how the much waste is generated and handled by 
the countries across the globe. The analysis of the project aims to ponder upon the insights 
to dig into the data to:
1. Find the countries that generated the most waste per year in tons
2. Find the countries that generate the most waste per person per year in pounds.
3. Anlayze the percentage of countries that make their waste managment data available to their public.
4. Analyze how many of these countries fall under high, medium and low GDP.
5. Plot and analyze if the country falls under high, medium, low to medium or low income country VS total waste generated.

# Make sure to Run it on Google Collab to see Graphs

# Relevant Packages
Make sure to use the command to install altair library: pip install altair vega_datasets.
The required packages to run this project can be found in requirement.txt file.

# 5 Features Used for the requirements of the project
1. Reading a data file from a CSV
2. Cleaning data by dropping columns that are not required for the analysis. For example:
    i. region_id
    ii. composition_glass_percent
    iii. other_information_national_agency_to_enforce_solid_waste_laws_and_regulations
3. Dropping rows with no or NA data
4. Replacing NA values with "NO"
5. Changing and mappuing code values to understandable format.
6. Analyzing the data using different python  built in functions
7. PLotting the data using library "altair"


# File to run
All the project code is complied into a single notebook named "explore.ipynb".
Run this file to run and view the project.


# DESCRIPTION OF THE DATA USED FOR ANALYSIS
**iso3c** - Abbrevation of the country
- **country_name** - Name of the Country
- **gdp** - GDP of the country in Billions for the year 2019
- **composition_food_organic_waste_percent** - Percentage of organic waste generated per yer.
- **composition_glass_percent** - Percentage of glass waste 
- **composition_metal_percent** - Percentage of metal waste
- **composition_other_percent** - Percentage of all other waste
- **composition_paper_cardboard_percent** - Percentage of paper cardboard waste
- **composition_plastic_percent** - Percentage of plastic waste
- **other_information_national_agency_to_enforce_solid_waste_laws_and_regulations** - If there exists a national agency in the country to enforce the laws.
- **other_information_national_law_governing_solid_waste_management_in_the_country** - If there exists a national law for waste mangement in the country.
- **other_information_summary_of_key_solid_waste_information_made_available_to_the_public** - If the information of the waste managemnet is made available to public.
- **population_number_of_people** - Total population of the country.
- **e_waste_tons_year** - Amount of e-waste generated/year.
- **total_waste_generated** - Amount of total waste generated by the country/year