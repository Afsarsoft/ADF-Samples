# ADF-Samples
ADF Samples <br />

## Pipeline: 01_plCopyOneTextFile
Description: Copy one Text/CSV file from one folder to another folder in BLOB <br />
Components: Copy data <br />

## Pipeline: 02_plCopyAllTextFiles
Description: Copy all Text/CSV files from one folder to another folder in BLOB <br />
Components: Get Metadata, ForEach, Copy data <br />
Background: https://www.youtube.com/watch?v=duyr9tPh_Yk&list=PLm7Nm9btqfe3QNbrLY-Vyu8-wh3EanG6t

## Pipeline: 03_plGameImportData
Description: Load data from ADLS Gen2 for Game project<br />
Components: Stored Procedure & Copy data <br />
Note: For more info about Game project, please see https://github.com/Afsarsoft/SQL-Game <br /> 

## Pipeline: 04_plGameExportData
Description: Export data from Azure SQL DB to ADLS Gen2<br />
Components: Copy data <br />
Note: For more info about Game project, please see https://github.com/Afsarsoft/SQL-Game <br /> 

## Pipeline: 05_plGameExportDataDynamic
Description: Dynamically Export data from Azure SQL DB to ADLS Gen2<br />
Components: Lookup, ForEach, Copy data <br />
Note: For more info about Game project, please see https://github.com/Afsarsoft/SQL-Game <br /> 
Background: https://www.youtube.com/watch?v=KsO2FHQdILs
It is documented in https://microsoft-bitools.blogspot.com/2019/06/staging-with-azure-data-factory-foreach.html <br /> 