# New Jersey State Police Fatal Crash Database

>**info**
>This section of the CAT is currently in beta. Please read the tips in this document carefully to understand its use. Please [send us](mailto:thomas.hillman@rutgers.edu) your feedback if you would like to guide its development.

To access the NJSP Fatal Crash Database, enter the [**Numetric Workbooks**](https://cloud.numetric.com/workbooks#/) module as follows:

1. Hover your mouse over the Numetric logo on the top left corner of the screen
2. Click on the Numetric logo from the dropdown menu

![](/assets/workbooks.gif)

Once inside, select one of the three NJSP Fatal Crash Database workbooks based on your table of primary interest:

* To count fatal crashes, select the [**NJSP Fatal Crashes**](https://cloud.numetric.com/workbooks#/report2/fa9beed9-77ec-4605-a899-4e26a086bde0) workbook. 
* To count people involved in crashes \(including fatality counts\), click the [**NJSP Fatal People Involved**](https://cloud.numetric.com/workbooks#/report2/034c41ea-77da-47b8-a124-860e484e04ee) workbook. 
* To count vehicles involved, click on the [**NJSP Fatal Vehicles**](https://cloud.numetric.com/workbooks#/report2/7f21e70e-f9de-4b25-934e-06e6908fe129) workbook. 

The mechanics of querying and exporting data from the NJSP Fatal Crash Database are the same as for all other CAT modules. See the [**Querying Crashes**](../chapter1/filtering-crashes.md) and [**Exporting Data**](../chapter1/exporting-data.md) pages for further information about those features.

The underlying data and design of the NJSP Fata Crash Database workbooks, as well as a list of searchable terms in the NJSP Fatal Crash Database, are different from the other workbooks and the Roads module. Below are details about the underlying data in the NJSP Fatal Crash Database and examples of questions and outputs from the workbooks.

## [NJSP Fatal Crashes](https://cloud.numetric.com/workbooks#/report2/fa9beed9-77ec-4605-a899-4e26a086bde0)

The [**NJSP Fatal Crashes**](https://cloud.numetric.com/workbooks#/report2/fa9beed9-77ec-4605-a899-4e26a086bde0) workbook uses the NJSP Fatal Crashes table as a base table. As a result, all charts, graphs, tables, and totals reflect a count of **crashes** where a fatality occurred. Some examples of questions that could be answered using the[**NJSP Fatal Crashes**](https://cloud.numetric.com/workbooks#/report2/fa9beed9-77ec-4605-a899-4e26a086bde0) workbook are the following:

> How many fatal **crashes** occurred in New Jersey in 2012-2016?
>
> Which counties had the highest frequency of fatal **crashes**?
>
> How many fatal **crashes** occurred where alcohol or drug use was involved on Interstate 297?

<!-- -->
>**tip**
>Bear in mind that the [**NJSP Fatal Crashes**](https://cloud.numetric.com/workbooks#/report2/fa9beed9-77ec-4605-a899-4e26a086bde0) workbook presents data joined to the crash table. As a result, counts and totals from this workbook will be structured as follows:

>* Number of crashes where a crash attribute was applicable \(eg. municipality, year, time of day, route\)
>* Number of crashes where anyone was involved with a particular person attribute \(eg. BAC level range, age, person type\)
>* Number of crashes where any vehicle was involved with a particular vehicle attribute \(eg. vehicle type\)

## [NJSP Fatal Involved](https://cloud.numetric.com/workbooks#/report2/034c41ea-77da-47b8-a124-860e484e04ee)

The [**NJSP Fatal Involved**](https://cloud.numetric.com/workbooks#/report2/034c41ea-77da-47b8-a124-860e484e04ee) workbook uses the People Involved table as a base table. All Drivers involved in fatal crashes in New Jersey since 2006 are included, whether they survived the crash or were deceased. **For non-drivers, only those who died as a result of the crash are included** \(eg. pedestrians, bicyclists, or occupants who survived the crash are not included, but deceased pedestrians, bicyclists, and occupants are included in the database\).

All charts, graphs, tables, and totals reflect a count of **people** that were involved in fatal crashes. This count includes all drivers plus deceased pedestrians, bicyclists, and other \(non-driver\) vehicle occupants. Some examples of questions that could be answered using the [**NJSP Fatal Involved**](https://cloud.numetric.com/workbooks#/report2/034c41ea-77da-47b8-a124-860e484e04ee) workbook are the following:

> How many **pedestrians** were killed who had a BAC test result of 0.05 or greater?
>
> What months are **bicyclists** most often killed in shore counties versus non-shore counties?
>
> How many **drivers** aged 65 or over were involved in fatal crashes? How many of them were killed? How many survived?

<!-- -->
>**tip**
Bear in mind that the [**NJSP Fatal Involved**](https://cloud.numetric.com/workbooks#/report2/034c41ea-77da-47b8-a124-860e484e04ee) workbook is joined to the \(people\) Involved level via the crash table. As a result, counts and totals from this workbook will be structured as follows:

>* Number of people involved in crashes where a crash attribute was applicable \(eg. municipality, year, route\)
>* Number of people involved in crashes who fit a given set of person involved attributes \(eg. age, person type, BAC range\)
>* Number of people involved in crashes where some vehicle was also involved with a particlar vehicle attribute \(eg. vehicle type\) \

<!-- -->
>**danger**
>NOTE: This count reflects all people who were involved in a crash where selected vehicle attributes were involved, NOT a count of people who had that particular vehicle attribute for their own vehicle. 

>For example you could produce a count of pedestrians killed in crashes with a box truck, or the number of drunk drivers involved in crashes where a box truck was also involved \(but NOT the number of drunk drivers who were driving box trucks\).

## [NJSP Fatal Vehicles](https://cloud.numetric.com/workbooks#/report2/7f21e70e-f9de-4b25-934e-06e6908fe129)

The [**NJSP Fatal Vehicles**](https://cloud.numetric.com/workbooks#/report2/7f21e70e-f9de-4b25-934e-06e6908fe129) workbook uses the Vehicle table as a base table. As a result, all charts, graphs, tables, and totals reflect a count of **vehicles** that were involved in fatal crashes. Some examples of questions that could be answered using the [**NJSP Fatal Vehicles**](https://cloud.numetric.com/workbooks#/report2/7f21e70e-f9de-4b25-934e-06e6908fe129) workbook are the following:

> How many **pick-up trucks** were involved in fatal crashes in New Jersey in 2012-2016?
>
> What types of **large vehicles** are most often involved in fatal crashes?
>
> How many **Box Trucks** were involved in crashes were Alcohol Use was a contributing factor?

<!-- -->
>**tip**
>Bear in mind that the [**NJSP Fatal Vehicles**](https://cloud.numetric.com/workbooks#/report2/7f21e70e-f9de-4b25-934e-06e6908fe129) workbook is joined to the Vehicle level via the crash table. As a result, counts and totals from this workbook will be structured as follows:

>* Number of vehicles involved in crashes
>* Number of vehicles involved in crashes where a particular crash attribute was applicable
>* Number of vehicles involved in crashes where a particular individual attribute was involved \(eg. BAC, age\)

<!-- -->
>**danger** 
>NOTE: This count reflects all vehicles that were involvd in a crash where a selected person involved attribute was also involved, not a count of vehicles where a person with that attribute was necessarily the driver. 

>For example, you could produce a count of box trucks involved in fatal crashes where any driver contributed alcohol or drug involvement to the crash, but NOT a count of box trucks where the driver was drunk\.

## Filterable Attributes

A list of attributes that can be used to filter the crash data presented in the _NJSP_ Fatal Crash Database Advanced Numetric Workbooks will be added soon to this tutorial. It will include brief descriptions of each attribute, how it was collected \(if applicable\), and a comprehensive list of all variable values. In the interim, feel free to filter by clicking on the interactive charts and graphs as described in the [**Querying Crashes**](../chapter1/filtering-crashes.md) tutorial, or use the [**Searchable Terms - Roads**](../chapter1/searchable-terms.md) dictionary as a guiding template for your filter in the top query bar.

