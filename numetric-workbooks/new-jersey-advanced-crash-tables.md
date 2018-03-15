# NJ Statewide Crash Database

> **info** Advanced querying for the NJ Statewide Crash Database is a new module. If you have feedback or any questions, feel free to [email us](mailto:thomas.hillman@rutgers.edu)!

To access the full New Jersey Statewide Crash Database for advanced querying, enter the [**Numetric Workbooks**](https://cloud.numetric.com/workbooks#/) module as follows:

1. Hover your mouse over the Numetric logo on the top left corner of the screen
2. Click on the Numetric logo from the dropdown menu

![](/assets/workbooks.gif)

Once inside, select one of the four New Jersey Statewide Crash Database workbooks based on your table of primary interest:

* To count crashes, select the [**Crash**](https://cloud.numetric.com/workbooks#/report2/8347e243-e9c9-4966-89f8-6b7c8c4376bb) workbook.
* To count drivers, select the [**Drivers**](https://cloud.numetric.com/workbooks#/report2/e282abec-0ae5-44f0-9db1-52649f5369b8) workbook.
* To count pedestrians or bicyclists, select the [**Pedestrians and Bicyclists**](https://cloud.numetric.com/workbooks#/report2/fd57b9e7-3b55-42bc-98b3-2a3547c9f55f) workbook.
* To count occupants \(including the driver\), click the [**Occupants**](https://cloud.numetric.com/workbooks#/report2/858d5c38-9959-4bc5-bdcd-905f342f85dd) workbook. 
* To count vehicles, click on the [**Vehicles**](https://cloud.numetric.com/workbooks#/report2/66b8b15e-f226-42ff-bcbc-550ab1b661db) workbook. 

The mechanics of querying and exporting data from the New Jersey Statewide Crash Database are the same as for all other CAT modules. See the [**Querying Crashes**](../chapter1/filtering-crashes.md) and [**Exporting Data**](../chapter1/exporting-data.md) pages for further information about those features.

The underlying data and design of the New Jersey Statewide Crash Database workbooks, as well as a list of searchable terms in the NJSP Fatal Crash Database, are different from the NSP Fatal Crash Database workbooks and the Roads module. Below are details about the underlying data in the New Jersey Statewide Crash Database and examples of questions and outputs from the workbooks.

## [**Crashes**](https://cloud.numetric.com/workbooks#/report2/8347e243-e9c9-4966-89f8-6b7c8c4376bb)

The [**Crashes**](https://cloud.numetric.com/workbooks#/report2/8347e243-e9c9-4966-89f8-6b7c8c4376bb) advanced workbook is very similar to the default Roads module. It uses the same New Jersey Statewide Crash Database Crash table as a base table. Some examples of questions that could be answered using the [**Crashes**](https://cloud.numetric.com/workbooks#/report2/8347e243-e9c9-4966-89f8-6b7c8c4376bb) workbook are the following:

> Of the **crashess** that occurred in my municipality, how many had a pedestrian over the age of 50 involved?
>
> In **crashes** over 65 involved in a high percentage of crashes in my municipality?
>
> How many **crashes** where a driver had a BAC between 0.05 and 0.08 resulted in a pedestrian death?
>
> What percentage of **crashes** where an improper lane change occurred resulted in a fatality?

<!-- -->
>**tip** In the advanced [**Crashes**](https://cloud.numetric.com/workbooks#/report2/8347e243-e9c9-4966-89f8-6b7c8c4376bb) workbook, all other tables (Drivers, Pededestrians and Bicyclists, Occupants, and Vehicles) are joined to the crash table to enable advanced querying.  As a result, all charts, graphs, tables, and totals reflect a count of **crashes** (unless otherwise specified in the chart title). As a result, counts and totals from this workbook will be structured as follows:
>
> * Number of **crashes** in crashes with a particular crash attribute (eg. municipality, year, time of day, route\)
> * Number of **crashes** with a particular driver/pedestrian or bicycle/occupant/vehicle attribute \(eg. BAC level, age, injury severity, contributing circumstances\)

## [Drivers](https://cloud.numetric.com/workbooks#/report2/e282abec-0ae5-44f0-9db1-52649f5369b8)

The [**Drivers**](https://cloud.numetric.com/workbooks#/report2/e282abec-0ae5-44f0-9db1-52649f5369b8) workbook uses the New Jersey Statewide Crash Database Driver table as a base table. As a result, all charts, graphs, tables, and totals reflect a count of **drivers** involved in crashes. Some examples of questions that could be answered using the [**Drivers**](https://cloud.numetric.com/workbooks#/report2/e282abec-0ae5-44f0-9db1-52649f5369b8) workbook are the following:

> Of the **drivers** involved in crashes aged 16-20, how many were under the influence of alcohol or drugs?
>
> Are **drivers** over 65 involved in a high percentage of crashes in my municipality?
>
> What percentage of seriously injured **drivers **crashed at an intersection versus a non-intersection?

<!-- -->
> **tip** The [**Drivers**](https://cloud.numetric.com/workbooks#/report2/e282abec-0ae5-44f0-9db1-52649f5369b8) workbook joins the crash table to the drivers table. As a result, counts and totals from this workbook will be structured as follows:
>
> * Number of **drivers** in crashes with a particular crash attribute (eg. municipality, year, time of day, route\)
> * Number of **drivers** with a particular driver attribute (eg. BAC level range, age, driver contributing circumstances\)

## [**Pedestrians and Bicyclists**](https://cloud.numetric.com/workbooks#/report2/fd57b9e7-3b55-42bc-98b3-2a3547c9f55f)

> **info** 
>To count only Pedestrians, select "No" on the "Is Bicyclist" Filter on the top right. To count only Bicyclists, select "Yes" on the "Is Bicyclist" filter on the top right. To count both pedestrians and biyclists, leave this filter unselected (default).

The [**Pedestrians and Bicyclists**](https://cloud.numetric.com/workbooks#/report2/fd57b9e7-3b55-42bc-98b3-2a3547c9f55f) workbook uses the New Jersey Statewide Crash Database Pedestrian and Bicyclist table as a base table. As a result, all charts, graphs, tables, and totals reflect a count of **pedestrians and/or bicyclists** involved in crashes. Some examples of questions that could be answered using the [**Pedestrians and Bicyclists**](https://cloud.numetric.com/workbooks#/report2/fd57b9e7-3b55-42bc-98b3-2a3547c9f55f) workbook are the following:

> Of the **bicyclists **involved in crashes, how many were under the influence of alcohol or drugs?
>
> Are **pedestrians **under 18 or over 65 involved in a high percentage of crashes in my municipality?
>
> What percentage of seriously injured **pedestrians **had their crash at an intersection versus a non-intersection?

<!-- -->
> **tip** The [**Pedestrians and Bicyclists**](https://cloud.numetric.com/workbooks#/report2/fd57b9e7-3b55-42bc-98b3-2a3547c9f55f) workbook joins the crash table to the pedestrian and bicyclist table. As a result, counts and totals from this workbook will be structured as follows:
>
> * Number of **pedestrians and/or bicyclists** in crashes with a particular crash attribute \(eg. municipality, year, time of day, route\)
> * Number of **pedestrians and/or bicyclists** with a particular pedestrian/bicyclist attribute \(eg. BAC level range, age, pedestrian/bicyclist contributing circumstances\)

## [**Occupants**](https://cloud.numetric.com/workbooks#/report2/858d5c38-9959-4bc5-bdcd-905f342f85dd)

> **info** 
>The Occupants table includes drivers. Seating position (where they were in the vehicle), saftey equipment used, and injury details are particularly useful attributes from this table.

The [**Occupants**](https://cloud.numetric.com/workbooks#/report2/858d5c38-9959-4bc5-bdcd-905f342f85dd) workbook uses the New Jersey Statewide Crash Database Occupants table as a base table. As a result, all charts, graphs, tables, and totals reflect a count of **occupants** involved in crashes. Some examples of questions that could be answered using the [**Occupants**](https://cloud.numetric.com/workbooks#/report2/858d5c38-9959-4bc5-bdcd-905f342f85dd) workbook are the following:

> How many unbelted **occupants** were in the front seat versus the back seat?
>
> Of all **occupants** involved in crashes aged 65 or older, what percentage were seriously injured?
>
> What percetage of **occupants** aged 12 or younger were using a child restrain system? If so, what kind?

<!-- -->
>**tip** The [**Occupants**](https://cloud.numetric.com/workbooks#/report2/858d5c38-9959-4bc5-bdcd-905f342f85dd) workbook joins the crash table to the occupants table. As a result, counts and totals from this workbook will be structured as follows:
>
>* Number of **occupants** in crashes with a particular crash attribute \(eg. municipality, year, time of day, route\)
>* Number of **occupants** with a particular occupant attribute \(eg. seating position, restraint use, age, sex\)

## [**Vehicles**](https://cloud.numetric.com/workbooks#/report2/66b8b15e-f226-42ff-bcbc-550ab1b661db)


> **info** 
>All driver actions leading up to and during the crash, including "Pre-Crash Action" (how the vehicle was being driven immediately prior to the crash), "Contributing Circumstances" (what behavior or external factors caused the driver to crash) and "Sequence of events 1-4" (what the vehicle hit after the crash began, in what order), are captured in the vehicle table.

The [**Vehicles**](https://cloud.numetric.com/workbooks#/report2/66b8b15e-f226-42ff-bcbc-550ab1b661db) workbook uses the New Jersey Statewide Crash Database Vehicles table as a base table. As a result, all charts, graphs, tables, and totals reflect a count of **vehicles **involved in crashes. Some examples of questions that could be answered using the [**Vehicles**](https://cloud.numetric.com/workbooks#/report2/66b8b15e-f226-42ff-bcbc-550ab1b661db) workbook are the following:

> Are large **vehicles** \(eg trucks and buses\) disproportionately involvd in serious injury or fatal crashes in my municipality?
>
> How many **vehicles** involved in crashes were towed away from the scene versus driven away?
>
> Of the **vehicles** involved in severe injury or fatal crash, what percentage had hazardous materials on board?

<!-- -->
>**tip** The [**Vehicles**](https://cloud.numetric.com/workbooks#/report2/66b8b15e-f226-42ff-bcbc-550ab1b661db) workbook joins the crash table to the vehicles table. As a result, counts and totals from this workbook will be structured as follows:
>
>* Number of **vehicles** in crashes with a particular crash attribute \(eg. municipality, year, time of day, route\)
>* Number of **vehicles** with a particular vehicle attribute \(eg. vehicle type, vehicle make, vehicle year, special function vehicle\)

## Filterable Attributes

A list of attributes that can be used to filter the crash data presented in the _NJ Statewide Crash Database_ advanced Numetric Workbooks has been compiled and will be added soon to this tutorial. It will include brief descriptions of each attribute, how it was collected \(if applicable\), and a comprehensive list of all variable values. In the interim, feel free to filter by clicking on the interactive charts and graphs as described in the [**Querying Crashes**](../chapter1/filtering-crashes.md) tutorial, or use the [**Searchable Terms - Roads**](../chapter1/searchable-terms.md) guide as a guiding template for your filter in the top query bar.

