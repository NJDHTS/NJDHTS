# Querying Crashes

Querying, or _filtering_, is the first step in a crash analysis, reducing the entire database \(over 3 million crashes since 2006\) to a manageable set of records for your analysis.

The way you filter will depend on what information, or values, you're looking for, and the scope of your analysis.

We'll review how to filter using the default Roads module that loads after you log in to the CAT.

## Filtering Methods

You can use any filtering method in conjunction with another. Filters are cumulative, so each additional one you apply will further limit the total number of records that fit all the specified filter criteria.

### Interactive Chart & Graph Filtering

The most intuitive way to filter crashes is by clicking on the interactive charts and graphs found throughout the Crash Analysis Tool. All charts will automatically adjust their totals based on any filters that are applied \(either by clicking to apply filters, or using one or more of the filtering methods below\). Chart and graphs provide totals based on the underlying data table \(they are not limited to "geocoded" crashes, or those with X and Y coordinates, but rather give the true total of any crashes in the database that fit the specified filters\).

Let's take the folloiwng example: Can we find crashes between the years of 2012 and 2016, where there was pedestrian involvement, in the municipality of New Brunswick?

##### Crash Year

Crash years are displayed in the right hand filter column. Just click and drag to select the years you want.

![](/assets/filter_year_optimized.gif)

You should see the total crashes in our query dropped from the total of 3.2 million \(2006-2016\) to 1.4 million for our specified year range.

##### Pedestrian Involvement

To capture all pedestrian involved crashes, make sure to always use the "Crash Attributes" field \("Crash Type" alone does not capture some pedestrian involved crashes\). "Crash Attributes" is a calculated field that correspond to the New Jersey Strategic Highway Safety Plan definitions for each safety emphasis area. Examples include Pedestrian Involved, Bicycle Involved, and Alcohol Involved. Let's filter based on Pedestrian Involved: go to "More Stats", find "Crash Attributes", and select Pedestrian.

![](/assets/click_filter_attribute.gif)

Now you should see the total crashes fell again from 1.4 million to 26 thousand, the number of pedestrian involved crashes in New Jersey from 2012-2016.

##### Municipality

Now let's further filter to just the municipality we're interested in, in this case New Brunswick. Under "More Stats", find "Municiplity" and hover over the chart until you find New Brunswick. Click on New Brunswick to apply the filter.

![](/assets/click_municipality.gif)

We have now filtered the data down to just over 300 pedestrian involved crashes in New Brunswick from 2012-2016. You could continue to explore the data in the Crash Analysis Tool, or check out the [Exporting Data ](/chapter1/exporting-data.md)page to learn to export for further analysis.

#### Filter Bar

The filter bar works exactly the same way as the Interactive Charts & Graphs, and allows for precise querying of the crash data based on the values you're looking for. Simply type in what you want to search for, scroll to the correct category \(for example: make sure to scroll down to "Municipality" for municipality names\). Let's take that same example as above, and see how quickly and easily we can create it using the filter bar. After you type each item, make sure to select it from its corresponding category in the drop-down menu. You may have to scroll through the drop-down menu to find the right category.

* 2012
* 2013
* 2014
* 2015
* 2016
* Pedestrian Involved
* New Brunswick



Now you try: take out pedestrian involvement and replace it with bicycle involvement. What changed in the crash totals? Are there any differences in the severity charts between these crash types?

#### Route Filter

Any crash that occurred along a numbered route can be filtered based on that route number. In addition, if you know the mileposts you're interested in searching, you can specify those as well.

The following video gives an overview of route filtering using Numetric. Note that New Jersey routes can be searched by their number directly: for example, for Interstate 295, simply type the number 295, or for County Road 518, simply type 518. Below is an informational video introduction to route filtering.

[https://www.youtube.com/watch?v=RJmS\_wV\_6pg](https://www.youtube.com/watch?v=RJmS_wV_6pg)

### Spatial Filter

Spatial filters allow you to analyze crashes visually at an intersection or along a stretch of road. Because spatial filters are map-based, they only capture those crashes that have geocoded crash information \(currently approximately 70% of all crashes\). Below is a quick tutorial video on how to use a spatial filter. Note that currently spatial filters can only create square boxes, although abnormal polygon based selection is coming in a future Numetric release.

[https://www.youtube.com/watch?v=lKSkkm2seTg](https://www.youtube.com/watch?v=lKSkkm2seTg)

### Save and Share a Query

Now that you've spent some time filtering just the crashes you want for your analysis, let's make sure you can come back and find those same crashes in the future, or share them with a colleague.

To save a query, simply click the "Save" button beside the top filter bar:

--Gif tutorial for saving--

Once you've saved a query, to share it, simply click the share icon![](/assets/share_icon_4.png)on the right hand side of the screen at the top \(just below your user name:

--Gif tutorial for sharing--

Wow, that was a lot of informatino to take in. Take a break before tackling the next section.

