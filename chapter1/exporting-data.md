# Exporting Data

To export data from the CAT as a .csv file \(for use in excel, Google MyMaps, ArcGIS, etc.\) follow these steps:

## 1. Query the Data

Ensure you have the data filtered to only what is relevant for your project. For further help on how to filter data, follow the [**Querying Crashes**](/filtering-crashes.md) tutorial.

## 2. Prepare the Columns

Once your data is queried, to prepare your columns of data for export. Click on the "Table" tab \(in the top middle of the screen, under the filter bar\). At the bottom left of the screen, select the "Columns" button to display which columns are active. Select the columns you want to activate or deactivate in your exported table.

![](/assets/columns2.gif)

Some examples of commonly activated columns for data export include the following:

| Common Columns Selected for Export |
| :--- |
| Pedestrian Involved |
| Bicyclist Involved |
| Alcohol Involved |
| Drugged Driving Involved |
| Unsafe Speed Involved |
| Crash Location \(street name where crash occurred\) |
| Route \(route number where the crash occurred\) |
| GPS Coordinates \(eg. "XWGSLONG" and "YWGSLat" for GoogleMy Maps or "X" and "Y" for ArcGIS\) |

## 3. Select the GPS Coordinates

Make sure to include GPS cooridnates if you'll be making a map. "XWGSLong" and "YWGSLat" are selected for export by default, and work for use in Google My Maps. Select the "X" and "Y" columns instead if using ArcMap.

## 4. Download the CSV

Click the CSV download arrow ![](/assets/csv_download_button.png) to download the .csv file of each crash indicdent \(row\) that fits your query, with the crash attributes \(columns\) you selected for excel analysis or map display.

![](/assets/csv_export2.png)

