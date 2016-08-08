XITSAP1 is an Excel tool to retrieve records from any SAP tables.


#Download

Get the file: XITSAP1_v01r_RFC_READ_TABLE.xls (zip)

#Feature

 1. Download SAP tables directly into Excel
 2. User can specify any tables to retrieve
 3. User can specify which fields to retrieve (planned in future development)
 4. User can specify condition of records to select (planned in future development)
 
#Usage example

1. Fill in SAP System connection parameters
2. Specify SAP Table name
3. Click Get Definition
4. Specify which field and what condition to retrieve
5. Click Read Table

#Requirement

 - Run on Microsoft Excel 2003/2007/2013/2016
 - Requires excel macro enabled
 - SAP client library installed on local PC
 - User has sufficient access to SAP R/3


#Specification

 - RUn as Excel VBA Macro
 - SAP records are retrieved by RFC call to: RFC_READ_TABLE
 - Currently limited to retrieve first 512 bytes of the SAP record

#License

- GNU AGPLv3
