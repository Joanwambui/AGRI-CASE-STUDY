# AGRI-CASE-STUDY
A python implemented project to answer the following questions based on the datasets provided: Checking for erroneous data: inconsistencies, outliers then conducting an analysis based on the objectives provided.
	Tasks
	1. Merge the three forms using the field labelled @case_id using Google sheet, Excel, R, Python or whichever tool you deem fit.
	2. You are to find enumerators who are likely not entering correct data (use username column to identify enumerators).  Some indications of this are:
	               1. Crazy box dimensions
	               2. False zero yields
	               3. Dry weight exceeding wet weight
	               4. Non-compliant data sets i.e no box dimension yet there is yield data captured. Zero wet weight yield but greater than zero dry weight, harvest crop mixed with other crops
	               5. Note that other variables in the dataset might also explain funny results, check other variables.  You can also look for those types of variables. 
	3. Use the box placement latitude and longitude, to come up with a spatial distribution of the data points on a map (you can use tools such as QGIS, Google Maps, ArcGIS or whichever tool you deem fit).  Consider this as well when assessing enumerator performance
	4. Compute the average yield in Mt/Ha for each observation, using the dry weight
	5. Create filters in a new column or columns to determine which types of yields we should consider outliers or errors and fill those columns so that we can filter the outliers on and off as needed. (if using code, clearly show these filters)
	6. Identify major problems affecting the crops per district or state. Use box1_problem column. Is there consistency?
![Uploading image.png…]()
