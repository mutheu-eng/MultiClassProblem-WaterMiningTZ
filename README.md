# MultiClassProblem-WaterMiningTZ
Can I predict which water pumps are faulty?

Using data from Taarifa and the Tanzanian Ministry of Water, I predict which pumps are functional, which need some repairs, and which don't work at all. 

I Predict one of these three classes based on a number of variables about what kind of pump is operating, when it was installed, and how it is managed. 

A smart understanding of which waterpoints will fail can improve maintenance operations and ensure that clean, potable water is available to communities across Tanzania.

The data is quite messy but with the programming tools availbale I manage to clean and transform it to actionable insights helping, citizens of Tanzania.

APPROACHES TAKEN: 

1. Data Familirization: I understand the columns in the data and their meaning, I check the data types of the columns, Inconsistencies in the data, misising values, duplicated values, outliers etc.
   
3. Decide the approcah I will use in dealing with the missing values, inconsistencies, data types and outliers,  -these are but a few of the things that highly impact the accuracy of the insights uncovered and the models performance, Therefore, the approach taken is key determinant of the outcomes.

5. With the missing values, I go with the approcah of filling in with the MODE since my columns are categorical, for duplicates I drop them, Outliers I remove them, having detected them using the Z-score approach.

7. I perform the EDA

THE LABELS IN THE DATASET:

functional - the waterpoint is operational and there are no repairs needed

functional needs repair - the waterpoint is operational, but needs repairs

non functional - the waterpoint is not operational
   
   FEATURES IN THE DATA:
   
amount_tsh - Total static head (amount water available to waterpoint)

date_recorded - The date the row was entered

funder - Who funded the well

gps_height - Altitude of the well

installer - Organization that installed the well

longitude - GPS coordinate

latitude - GPS coordinate

wpt_name - Name of the waterpoint if there is one

num_private - 

basin - Geographic water basin

subvillage - Geographic location

region - Geographic location

region_code - Geographic location (coded)

district_code - Geographic location (coded)

lga - Geographic location

ward - Geographic location

population - Population around the well

public_meeting - True/False

recorded_by - Group entering this row of data

scheme_management - Who operates the waterpoint

scheme_name - Who operates the waterpoint

permit - If the waterpoint is permitted

construction_year - Year the waterpoint was constructed

extraction_type - The kind of extraction the waterpoint uses

extraction_type_group - The kind of extraction the waterpoint uses

extraction_type_class - The kind of extraction the waterpoint uses

management - How the waterpoint is managed

management_group - How the waterpoint is managed


payment - What the water costs

payment_type - What the water costs

water_quality - The quality of the water

quality_group - The quality of the water

quantity - The quantity of water

quantity_group - The quantity of water

source - The source of the water

source_type - The source of the water

source_class - The source of the water

waterpoint_type - The kind of waterpoint

waterpoint_type_group - The kind of waterpoint
