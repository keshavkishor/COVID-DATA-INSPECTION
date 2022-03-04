# COVID-DATA-INSPECTION

Covid data insights gathering using MySQL workbench and PowerBI

Link for downloading MySQL workbench- https://dev.mysql.com/downloads/workbench/
I will be using web version of MS Excel and PowerBI.

For downloading the dataset required in this project click the below link.
Link: https://ourworldindata.org/covid-deaths
The file will be downloaded in .csv format.

Upload the file in MS Excel and we will make two diffrent tables haing different columns with the help of that.
For editing purpose .csv file will get converted to .xlsx format in MS Excel
1. Covid Deaths- This table will include all information and data related to death of people during covid. eg: Country, Continent, Date, Total Population, Number of People got infected, Total number of deaths etc.
2. Covid Vaccination- This table will include all the information and data related to people who get vaccinated. eg: Country, Continent, Date, Total Population, Number of People got Vaccinated, Percent of people got Vaccinated etc.

After making two different tables convert them back to .csv form, as MySQL workbench accepts the data in .csv format
Use the below link to convert your files from .xlsx to .csv format
Link: https://cloudconvert.com/xlsx-to-csv

After this upload the data(.csv format) in MySQL workbench and run the commands given in Covid Data Code file.

After creating the last view from your data go to the view section of your current database and right-click on that, from there you can download your insights tables on desktop in .csv format by clicking on the option called Table Data Export Wizard. 

Then upload this data in MS Excel in a single worksheet so that from there we can easily upload the data in PowerBI for dashboard making.
