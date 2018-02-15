# New Jersey State Police Fatal Crash Database

To access the NJSP Fatal Crash Database, enter the Numetric Workbooks module as follows:

1. Hover your mouse over the Numetric logo on the top left corner of the screen
2. Click on the Numetric logo from the dropdown menu

--gif showing how to get to workbooks --

Once inside, select one of the three NJSP Fatal Crash Database workbooks based on your table of primary interest:

* To count fatal crashes, select the NJSP Fatal Crashes workbook. 
* To count people involved in crashes \(including fatality counts\), click the NJSP Fatal People Involved workbook. 
* To count vehicles involved, click on the NJSP Fatal Vehicles workbook. 

The mechanics of querying and exporting data from the NJSP Fatal Vehicles database are the same as for all other CAT modules. See the [Querying Crashes ](/chapter1/filtering-crashes.md)and [Exporting Data](/chapter1/exporting-data.md) pages for further information about those features.

The underlying data and design of the NJSP Fatal Crash workbooks, as well as a list of searchable terms in the NJSP Fatal Crash Database, are different from the other workbooks and the Roads module. Below are details about these aspects of using workbooks to explore the NJSP Fatal Crash Database.

## NJSP Fatal Crashes

The NJSP Fatal Vehicles workbook uses the Vehicle table as a base table. As a result, all charts, graphs, tables, and totals reflect a count of **vehicles** that were involved in fatal crashes. Some examples of questions that could be answered using the NJSP Fatal Vehicles workbook are the following:

> How many **pick-up trucks** were involved in fatal crashes in New Jersey in 2012-2016?
>
> What types of **large vehicles** are most often involved in fatal crashes?
>
> How many **Box Trucks** were involved in crashes were Alcohol Use was a contributing factor?

Bear in mind that the NJSP Fatal Vehicles workbook is joined to the Vehicle level via the crash table. As a result, counts and totals from this workbook will be structured as follows:

 \# of vehicles involved in crashes

\# of vehicles involved in crashes where a particular crash attribute was applicable

\# of vehicles involved in crashes where a particular individual attribute was involved

### NJSP Fatal People Involved

The NJSP Fatal Involved workbook uses the People Involved table as a base table. All Drivers involved in fatal crashes in New Jersey since 2006 are included, whether they survived the crash or were deceased. **For non-drivers, only those who died as a result of the crash are included** \(eg. pedestrians, bicyclists, or occupants who survived the crash are not included, but deceased pedestrians, bicyclists, and occupants are included in the database\). 

All charts, graphs, tables, and totals reflect a count of **people** that were involved in fatal crashes. This count includes all drivers plus deceased pedestrians, bicyclists, and other \(non-driver\) vehicle occupants. Some examples of questions that could be answered using the NJSP Fatal Involved workbook are the following:

> How many **pedestrians** were killed who had a BAC test result of 0.05 or greater?
>
> What months are **bicyclists **most often killed in shore counties versus non-shore counties?
>
> How many **Box Trucks** were involved in crashes were Alcohol Use was a contributing factor \(for either the truck driver or another driver\)?

Bear in mind that the NJSP Fatal People Involved workbook is joined to the People Involved level via the crash table. As a result, counts and totals from this workbook follow this format:

 \# of people involved in crashes

\# of people involved in crashes where a particular crash attribute was applicable

\# of people involved in crashes where a particular person-level attribute was applicable \(eg. person type, BAC result\)

\# of people involved in crashes where a particular vehicle attribute was also involved in the crash \(Warning: this count reflects any crash where that vehicle attributes were involved, not a count of people who had that particular vehicle attribute. For example, a count of pedestrians killed in crashes with a box truck, or the number of drunk drivers involved in crashes where a box truck was also involved \(NOT the number of drunk drivers of box trucks\).

### NJSP Fatal Vehicles

The NJSP Fatal Vehicles workbook uses the Vehicle table as a base table. As a result, all charts, graphs, tables, and totals reflect a count of **vehicles** that were involved in fatal crashes. Some examples of questions that could be answered using the NJSP Fatal Vehicles workbook are the following:

> How many **pick-up trucks** were involved in fatal crashes in New Jersey in 2012-2016?
>
> What types of **large vehicles** are most often involved in fatal crashes?
>
> How many **Box Trucks** were involved in crashes were Alcohol Use was a contributing factor?

Bear in mind that the NJSP Fatal Vehicles workbook is joined to the Vehicle level via the crash table. As a result, counts and totals from this workbook will be structured as follows:

 \# of vehicles involved in crashes

\# of vehicles involved in crashes where a particular crash attribute was applicable

\# of vehicles involved in crashes where a particular individual attribute was involved

### Filterable Attributes

A list of attributes that can be used to filter the crash data presented in the _NJS\_SP_ Fatal Crash Database \_advanced Numetric Workbooks will be added soon to this tutorial. Included are brief descriptions of each attribute, how it was collected \(if applicable\), and a comprehensive list of all variable values.

