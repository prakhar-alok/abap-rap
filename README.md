# abap-rap
## ABAP RESTful Application Programming

- RAP is an architecture for developing SAP HANA-optimized Odata services for SAP Fiori capplications or Web API's.
- It is available in SAP BTP ABAP environment, S/4 HANA Cloud and AS ABAP 7.56.
- It is based on CDS and ABAP based custom logic and uses SAPUI5 for UI.

## RAP Architecture

**Service Consumption** -> SAP Fiori UI or Web API's  
**Business Service** -> Service Bunding, Service Definition  
**Data Modeling and Behavior** -> CDS Data Modeling, Behavior Definition and Behavior Implementation  

## ABAP programming model evolution
- **Classic ABAP programming**
    - Freestyle ABAP code
    - Screen programming
- **ABAP programming model for Fiori**
    - SEGW
    - Odata.Publish
    - CDS and CDS based BOPF
- **ABAP RESTful Application Programming Model**
    - Business service
    - CDS
    - Behavior definition ...

## RAP Model has 3 layers
1. Data Modeling and Behavior
2. Business service
3. Service Consumption

## Basic steps of RAP application development
**Data Modeling and Behavior**
1. Create a table
2. Create root and projection/consumption CDS entities
3. Create Metadata extension
4. Create Behavior definition

**Business service**
1. Create service definition
2. Create service binding

**Service Consumption**
1. Create FIORI elements app
