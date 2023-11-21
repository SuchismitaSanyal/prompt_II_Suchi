# prompt_II_Suchi
The primary objective of the analysis from a business perspective Business is to appropriately price the used car. The Data mining goals is to identify the attributes of the car that influence the pricing of the used car.
This task involves more detailed fact-finding about all of the resources, constraints, assumptions, and other factors that should be considered in determining the data analysis goal and project plan.

Described the data that has been acquired, including the format of the data, the quantity of data (for example, the number of records and fields in each table), the identities of the fields, and any other surface features which have been discovered. Evaluate whether the data acquired satisfies the relevant requirements.


There are 426880 rows and 18 columns. There are a lot of missing data for the columns manufacturer     4.13 %, model           1.24%, condition       40.78% , cylinders       41.62%, fuel             0.70%, odometer         1.03%, title_status     1.93%, transmission     0.6%, VIN             37.72% , drive           30.58% , size            71.76%, type            21.75%, paint_color     30.5%.
Added a column ‘Age_of_car’ which is calculated from ‘year’ and current year.

For numeric columns like, 'price', 'cylinders', 'odometer', 'Age_of_car', substituted the mean of the column for the missing values.
For categorical columns like 'condition','fuel','title_status','transmission','drive','size', performed encoding.
Removed the null values and still there was 426880 rows of data. 
The features which play dominant role in determining the price are  'condition_new', 'condition_salvage', 'title_status_missing', 'title_status_parts only'.

