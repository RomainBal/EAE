# Heinekein Sales Metrics
This is the final assignment using Power BI, from the Data Visualization course at the Big Data & Analytics Masters @ EAE class of 2021. The assignment uses mocked-up data as input provided by the professor:
•	*.txt files in comma-separated-values format, that mimic Heineken Sales data from years 2015 and 2016 
•	*.txt files in comma-separated-values format, that mimic Heineken Sales Budget data from the same time period.
•	*.txt files in comma-separated-values format, that mimic Nielsen overall market Sales data from the same time period.
•	*.xls files that represent Customer, Product and Salesman master data. The assignment purpose is to provide sales insights and recommendations, backed up by visualizations.

![123307883-4d287200-d523-11eb-9f63-4594f4517122](https://user-images.githubusercontent.com/85830810/125596767-47ab4398-3554-4cd2-8ac2-aad34d5db33a.png)


Professors:

•	Daniel Jiménez

Team:

•	Romain Baleynaud (GitHub)

•	Henrique Avila

•	Joseph Higaki (GitHub)

•	Raquel Ganuza

•	Ziyad Ashukri


=Highlights

Data Cleansing

•	Removed exact duplicates creating a row hash identity column.

•	Remove rows having alphanumeric Product Codes, as they were proven invalid.


Dimension Data Customization
The input data was generic, it was only relevant for us the fact tables measures and master data ids. So, on top of those master data records we customized attributes such as codes, names and pictures, resulting in an OLAP Snowflake schema, where there are auxiliary tables to the dimensions to store those customizations such as:
•	Customer Name
•	Product Brand, Capacity and Container Type
•	Account Manager Name
•	Director Name & Pictures

![123308110-9082e080-d523-11eb-85d8-9b120008ccac](https://user-images.githubusercontent.com/85830810/125596817-d731cf9d-2137-471f-a8c1-29a7287eb6f3.png)


Sales vs Budget Dashboard

![123312254-5ec04880-d528-11eb-8fd6-2f8399c6e8cc](https://user-images.githubusercontent.com/85830810/125596731-110d3d94-ae8a-467a-987a-f639cc6b171b.png)


Summary:
[HEINEKEN DOCUMENTATION.pdf](https://github.com/RomainBal/Heineken_Sales_Metrics/files/6814981/HEINEKEN.DOCUMENTATION.pdf)
