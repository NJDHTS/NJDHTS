# Searchable Terms \(Roads\)

In order to find the data you're looking for in the CAT you'll need to know how to search for it. Since the NJTR-1 crash report form has over 140 fields, some of which have over 30 standard values, we have compiled this data dictionary for your use.

Below is a list of attributes that can be used to filter the crash data presented in the [Roads Module](https://njdhts.numetric.com/roads/crash-query#/) Included are brief descriptions of each attribute, how it was collected \(if applicable\), and a comprehensive list of all variable values.

### Searchable Terms

##### Alcohol Involved

Should show crashes where at least one person involved was under the influence of alcohol at the time of the crash.  This includes drivers, bicyclists and pedestrians. Vehicle occupants other than the driver are not part of this definition. This field is identical to the Crash Characteristics field where “Alcohol” is cited, and it is recommended to use the Crash Characteristics field for the most efficient searches.

* 1 – \(Yes\) 
* 0 – \(No\)

##### Bicyclist Involved

Shows crashes where at least one cyclist was involved in the crash. This field is identical to the Contributing Circumstance field where “Bicyclist” is cited and derived for analysis convenience. This field is identical to the Crash Characteristics field where “Bicyclist” is cited, and it is recommended to use the Crash Characteristics field for the most efficient searches.

* 1 – \(Yes\) 
* 0 – \(No\)

**Cell Phone Related**

Shows the crashes where the driver was cited for using their cell phone at the time of the crash. This field is populated through witness accounts and voluntary admission and may not include all crashes where cell phone was in use. This field is identical to the Driver Contributing Factors field where “Cell Phone” is cited, and it is recommended to use the Driver Contributing Factors field for the most efficient searches.

* 1 – \(Yes\) 
* 0 – \(No\)

##### Contributing Circumstances

Will appear in an array in a single column. Each vehicle should have two contributing circumstances and will array by vehicle \(e.g. Vehicle 1, Vehicle 2, Vehicle 3, etc.\). Example: Driver Inattention \(V1\), Following too Closely \(V1\), Driver Inattention \(V2\), None \(V2\). 

| Contributing Circumstances |  |
| :--- | :--- |
| Animals in Roadway |  |
| Backing Unsafely |  |
| Brakes |  |
| Control Device Defective or Missing |  |
| Defective Lights |  |
| Driver Inattention |  |
| Failed to Obey Traffic Control Device \(Driver/Pedalcycle\) |  |
|  |  |
|  |  |
|  |  |
|  |  |





Animals in Roadway

Backing Unsafely

Brakes

Control Device Defective or Missing

Defective Lights

Driver Inattention

Failed to Obey Traffic Control Device \(Driver/Pedcycle\)

Failed to Yield Right of Way to Vehicle/Pedestrian

Failure To Keep Right

Following Too Closely

Improper Lane Change

Improper Parking

Improper Passing

Improper Turning

Improper Use/Failed to Use Turn Signal

Improper Use/No Lights

Improper Work Zone

Improper/Inadequate Lane Markings

Mirrors

None \(Driver/Pedcycle\)

Obstruction/Debris In Road

Other

Other Driver/Pedalcyclist Action

Other Roadway Factors

Other Vehicle Factor

Physical Obstructions \(viewing\)

Road Surface Condition

Ruts/ Holes/ Bumps

Steering

Sunglare

Tires

Unknown

Unsafe Speed

Veh Coupling/Hitch/Safety Chains

Windows/Windshield

Wheels

Wipers

Wrong Way

County – County where the crash took place. ATLANTIC BERGEN BURLINGTON CAMDEN

3 \| P a g e

CAPE MAY CUMBERLAND ESSEX GLOUCESTER HUDSON HUNTERDON MERCER MIDDLESEX MONMOUTH MORRIS OCEAN PASSAIC SALEM SOMERSET SUSSEX UNION WARREN

Crash Characteristics – These are pre-calculated queries that are stored in an array if relevant to the individual crash event. It is preferred to search for these factors under Crash Characteristics to be sure you are querying the database most efficiently. In each of the cases below, the element is present. Examples: Bicyclist included one or more bicyclists, Curve-related is where crash occurred on a roadway curve.Bicyclist Curve Related Head-On Live Animal Motorcycle Older Driver Pedestrian Ran Off Road Unrestrained Passenger Work Zone Young Driver

Crash Date – The date the crash took place Any Crash Date. Format is 2016-04-25

Crash Location – Description of location where crash took place, typically the street name. Dynamic field – this is where you can type in the street the crash took place on. Keep in mind there may be many iterations of street name \(e.g. JFK Blvd, John F. Kennedy Blvd, JFK Boulevard\). Street names may have also been entered by their local name as well \(e.g. Main Street = Route 501\). Searches may not return all crashes until all variations of street names have been entered.

4 \| P a g e

Crash Month – Also available as sidebar filter. January February March April May June July August September October November December

Crash Type – Typically the first injury or damage-producing event. Also available as a sidebar filter. Animal Backing Encroachment Fixed Object Left Turn / U Turn Non-fixed Object Opposite Direction - Head On/Angular Opposite Direction - Side Swipe Other Overturned Pedalcyclist – Does NOT capture all Pedalcycle Crashes. Recommended to search for Bicyclist under “Crash Characteristics” Pedestrian – Does NOT capture all Pedestrian Crashes. Recommended to search for Pedestrian under “Crash Characteristics” Railcar-vehicle Right Angle Same Direction - Rear End Same Direction - Side Swipe Struck Parked Vehicle Unknown

Crash Year – Also available as sidebar filter. 2011 2012 2013 2014 2015

5 \| P a g e

DHTS RegionRegion 1 – \(Atlantic, Burlington, Camden, Cape May, Cumberland, Gloucester, Salem Counties\) Region 2 – \(Hunterdon, Mercer, Middlesex, Monmouth, Ocean, Somerset, Union Counties\) Region 3 – \(Bergen, Essex, Hudson, Morris, Passaic, Sussex, Warren Counties\)

DIRECTION\_FROM\_CROSS\_STREETNorth South East West

Direction of TravelNorth South East West Unknown

Distracted Driving Involved – Crashes defined where any driver involved had either Contributing Circumstance \(CC\) 1 or 2 cited as Driver Inattention. This is a count of crashes. This field is identical to the Driver Contributing Factors field where “Distracted Driving” is cited, and it is recommended to use the Driver Contributing Factors field for the most efficient searches. 1 – \(Yes\) 0 – \(No\)

Driver Contributing Factors - These are pre-calculated queries that are stored as an array. It is preferred to search under Driver Contributing Factors to be sure you are querying the database most efficiently. In each of the cases below, the element is present in the crash event. Examples: Distracted Driving is one or more drivers was cited as Driver Inattention as their first or second Contributing Circumstance; Drowsy Fatigued Driving is one or more drivers had a physical status of drowsy or fatigued. Alcohol Related Cell Phone In Use Distracted Driving Drowsy Fatigued Driving Drugged Driving Unsafe Speed

Drugged Driving – Defined as one or more drivers involved in the crash had the Driver Physical Status listed as “Drug Use \(Illicit\)” or “Medication.” This definition does not include crashes where “Alcohol and Drug Use \(Illicit or Medication\) was cited as the Driver Physical Status. This is a count of crashes. This field is identical to the Driver Contributing Factors field where “Drugged Driving” is cited, and it is recommended to use the Driver Contributing Factors field for the most efficient searches.

6 \| P a g e

1 – \(Yes\) 0 – \(No\)

Environmental Condition – Weather conditions at the time of the crash. Blowing Sand/Dirt Blowing Snow Clear Fog/Smog/Smoke Other Overcast Rain Severe Crosswinds Sleet/Hail/Freezing Rain Snow Unknown

Events – All Sequences of events \(1-4\) for each vehicle involved in the crash. This variable is stored as an array. Each vehicle should have up to four sequence of events. They cascade in order \(First, Second, Third, Fourth\) and by Vehicle number \(1, 2, etc.\). Bridge Overhead Structure Bridge Parapet End Bridge Pier or Support Bridge Rail Cargo / Equipment Loss or Shift Concrete Traffic Barrier Crossed Median / Centerline Culvert Curb Deer Ditch Downhill Runaway Embankment Equipment Failure Fell / Jumped From Vehicle Fence Fire Hydrant Fire/Explosion Guardrail End Guardrail Face Immersion Impact Attenuator / Crash Cushion Jackknife Light Standard

7 \| P a g e

MV In Transport MV In Transport/ Other Roadway Mailbox Other Other Animal Other Fixed Object Other Non Collision Other Non-Fixed Object Other Post/ Pole/ Support Other Traffic Barrier Overturn \(Rollover\) Parked MV Pedalcyclist Pedestrian Ran Off Road - Left Ran Off Road - Right Separation of Units Struck By Object Set In Motion By MV Thrown / Falling Object Traffic Sign Support Traffic Signal Standard Train / Trolley / Other Railcar Tree Unknown Utility Pole Work Zone or Maint. Equipment

First Sequence of Events - Will appear as an array. They will cascade in order of Vehicle number. Bridge Overhead Structure Bridge Parapet End Bridge Pier or Support Bridge Rail Cargo / Equipment Loss or Shift Concrete Traffic Barrier Crossed Median / Centerline Culvert Curb Deer Ditch Downhill Runaway Embankment Equipment Failure Fell / Jumped From Vehicle

8 \| P a g e

Fence Fire Hydrant Fire/Explosion Guardrail End Guardrail Face Immersion Impact Attenuator / Crash Cushion Jackknife Light Standard MV In Transport MV In Transport/ Other Roadway Mailbox Other Other Animal Other Fixed Object Other Non Collision Other Non-Fixed Object Other Post/ Pole/ Support Other Traffic Barrier Overturn \(Rollover\) Parked MV Pedalcyclist Pedestrian Ran Off Road - Left Ran Off Road - Right Separation of Units Struck By Object Set In Motion By MV Thrown / Falling Object Traffic Sign Support Traffic Signal Standard Train / Trolley / Other Railcar Tree Unknown Utility Pole Work Zone or Maint. Equipment

Functional Class – Functional class of the roadway where the crash occurred. Rural Interstate Rural Local Rural Major Collector Rural Minor Arterial Rural Minor Collector Rural Principal Arterial

9 \| P a g e

Unknown Urban Collector Urban Freeway/Expressway Urban Interstate Urban Local Urban Minor Arterial Urban Principal Arterial

Hazmat Involved – Shows the crashes where hazardous material was on board one of the vehicles involved in the crash. This is a count of crashes.1 – \(Yes\) 0 – \(No\)

Highway Type – Type of highway division as cited by reporting officer. Dual/Dual Divided Undivided Unknown

Horizontal Alignment – Horizontal alignment of the roadway as cited by reporting officer. Straight Curve Unknown

Intersection Not At Intersection At Intersection – Crashes cited as taking place inside the “box” At or near Railroad Crossing

Is Ramp – Crashes that took place on an entrance/exit ramp. NOT RAMP TO FROM

Jurisdiction Burlington County Bridge Commission County D.R.J.T.B.C. Delaware River and Bay Authority Delaware River Port Authority Municipal N.J.D.O.T. New Jersey Turnpike Authority

10 \| P a g e

Palisades Interstate Parkway Commission Port Authority of N.Y & N.J. South Jersey Transportation Authority Unknown

Lane Count – Number of Lanes in roadway \(e.g. 1, 2, 3\). Each individual lane in each roadway direction contributes to this count \(e.g. a two-way road with one lane in each direction would have Lane Count = 2\).

Light ConditionDark \(No Street Lights\) Dark \(Street Lights Off\) Dark \(Street Lights On\) Dawn Daylight Dusk Unknown

Location Direction –Nominal direction of the roadway where the crash occurred \(example: Interstate 78 East = East; Route 1 South = South\). As cited by recording officer. North South East West

Live Animal Involved – Crashes involving Live Animals. Includes cases where animal was not struck, but caused loss of control of vehicle resulting in a crash. This field is identical to the Crash Characteristics field where “Live Animal” is cited, and it is recommended to use the Crash Characteristics field for the most efficient searches. 1 – \(Yes\) 0 – \(No\)

Median TypeCurbed None Painted/Unprotected Positive Unknown Unprotected

MPO – Metropolitan Planning Organization DVRPC NJTPA

11 \| P a g e

SJTPO

Municipality – Municipality where the crash took place. Could differ from the Police Department field for calls taken by other departments.

Motorcycle Involved – Crashes involving a motorcycle. Could include multiple motorcycles. This is a count of crashes. This field is identical to the Crash Characteristics field where “Motorcycle” is cited, and it is recommended to use the Crash Characteristics field for the most efficient searches. 1 – \(Yes\) 0 – \(No\)

Older Driver Involved – At least one of the drivers involved was 65 years of age or older. This is a count of crashes. This field is identical to the Crash Characteristics field where “Older Driver” is cited, and it is recommended to use the Crash Characteristics field for the most efficient searches. 1 – \(Yes\) 0 – \(No\)

Pedestrians Injured – Total number of pedestrians and/or bicyclists injured in the crash. This is a count of individual pedestrians.

Pedestrians Killed – Total number of pedestrians and/or bicyclists killed in the crash. This is a count of individual pedestrians.

Police Department – Police department that responded to the crash event. Can vary from the Municipality where the crash occurred if a different department responded.

Pre Crash Vehicle Action – The action taking place for each vehicle leading up to the crash. Stored as an array corresponding to each vehicle involved in the crash \(e.g: a two-vehicle crash could have a Pre Crash Vehicle Action: Changing Lanes, Going Straight Ahead\). Array ordered by vehicle number. \(reserved\) – Blank Field Backing Changing Lanes Coming From Behind Parked Vehicle Crossing / Jaywalking Crossing at marked Crosswalk \(At Mid-Block\) Crossing at unmarked Crosswalk \(At Intersection\) Driverless / Moving Driving on Shoulder Getting On/Off Vehicle Going Straight Ahead Making Left Turn Making Right Turn \(not turn on red\) Making U Turn

12 \| P a g e

Merging/Entering Traf Lane Negotiating Curve Other Other Pedestrian Action Other Veh/Cyclist Action Other Working in Roadway Parked Parking Passing Pedestrian Off Road Playing in Road Pushing/Working on Vehicle Right Turn on Red Slowing or Stopping Standing/Lying/Kneeling Against Traffic Starting From Parking Starting in Traffic Stopped in Traffic Unknown Walking To/From School Walking/Jogging Against Traffic Walking/Jogging with Traffic Blank – blank field

Pedestrian Involved – Crashes where at least one pedestrian was involved in the crash. This is a count of crashes. This field is identical to the Crash Characteristics field where “Pedestrian” is cited, and it is recommended to use the Crash Characteristics field for the most efficient searches. 1 – \(Yes\) 0 – \(No\)

RAMP\_TO\_FROM\_ROUTE\_DIRECTION – Ramp direction at the location of the crash \(for crashes that occurred on highway ramps only\) as cited by reporting officer. North Bound South Bound East Bound West Bound

Road Character – Physical characteristics of the roadway, as cited by the reporting officer. Curve and Grade Curve and Hillcrest Curve and Level Straight and Grade Straight and Hillcrest

13 \| P a g e

Straight and Level Unknown

Road Divided By Barrier Median Curbed Median Grass Median Other Painted Median Unknown

Road Surface Type Blacktop Concrete Dirt Gravel Other Steel Grid Unknown

Road SystemCo. Auth. County Interstate Mun Auth Municipal Private Property State Highway State Park or Institution State/Interstate Authority US Govt Property Unknown

Route – State or County route number where the crash took place, as cited by reporting officer.Entered as numeric value \(i.e. 618 for Route 618\). Keep in mind local street names may have been used in place of Route number. Searching for the route number only may not return all of the crashes. \(example: Route 618 may also be Main Street and entered as Main Street, leaving Route number blank\). Searches may not return all crashes until all variations of street names and route numbers have been entered.

Route Suffix – Route suffix as cited by reporting officer.1

14 \| P a g e

2 3 4 5 6 A - Alternate B - Business C - Freeway EM – Mercer Alignment \(I-95 Only\) N S – Spur \(County Routes Only\) T – Truck \(Rt. 1 & 9 Only\) U – Upper \(State Route 139 Only\) W – Western Alignment \(NJ Turnpike, Rt. 9, Rt. 173\) X Z P – Pennsylvania Extension \(NJ Turnpike Only\)

Rural Or Urban Rural Unknown Urban

Severity – Will show the most severe injury sustained in the crash event. I.e. If one person was Killed, and 4 were moderately injured, the Severity will be marked as Fatal. PDO – Property Damage Only Fatal Incapacitating Injury Moderate Injury Pain

Single Vehicle – Indicates if this was a Single Vehicle Crash. This is a count of crashes. 1 – \(Yes\) 0 – \(No\)

Speed Limit –Speed limit according to NJ Straight Line Diagrams at based on the location of the crash. May differ from Posted Speed field, which is entered by the reporting officer on the crash report form at the time of the crash. 0 10 15

15 \| P a g e

20 25 30 35 40 45 50 55 65

SRI – Standard Route Identification number. 10-digit number used to identify roadways in NJ. SRI numbers can be found on the NJ Straight Line Diagrams.

Surface Condition – Condition of the roadway. Not to be confused with weather condition. \(i.e. It could be snowing, but the surface condition is “Wet”\). Dry Icy Oil Other Sand/ Mud/ Dirt Slush Snowy Unknown Water \(Standing/Moving\) Wet

Temp Traffic Control Zone Construction Zone Incident Zone Maintenance Zone Unknown Utility Zone

Total Incapacitated – Total persons, Motorists and Non-Motorists, that had an incapacitating injury as a result of the crash. This is a count of bodies.

Total Injured – Total persons, Motorists and Non-Motorists, that had any injury, excluding fatal injury, as a result of the crash. This is a count of bodies.

Total Killed – Total persons, Motorists and Non-Motorists, that were killed as a result of the crash. This is a count of bodies.

16 \| P a g e

Total Pedestrians Involved – Total Non-Motorists involved in the crash event. This also includes Bicyclists. This is a count of bodies.

Total Vehicles Involved – Total number of vehicles involved in the crash event.

Traffic Controls Present Adult Crossing Guard Channelization-Painted Channelization-Physical Flagman Flashing Traffic Control Lane Markings No Control Present Other Police Officer RR Watchman/ Gates/ etc School Zone \(Signs/Controls\) Stop Sign Traffic Signal Unknown Warning Signal Yield Sign

Unit of Measurement – Unit of measurement corresponding to the Distance to Cross Street element \(e.g. 200 Feet from the nearest cross street; 1 Mile from the nearest cross street\). Foot At – \(No distance\) Mile

Unrestrained Passenger – Indicates if one or more of the occupants within a motor vehicle involved in the crash were not wearing a seatbelt at the time of the crash. This field is identical to the Contributing Circumstance field where “Unrestrained Passenger” is cited, and it is recommended to use the Contributing Circumstance field for the most efficient searches. 1 – \(Yes\) 0 – \(No\)

Unsafe Speed Involved - Defined as a driver involved in the crash had either Contributing Circumstance 1 \(CC1\) or Contributing Circumstance 2 \(CC2\) cited as Unsafe Speed. This is a count of crashes. This field is identical to the Driver Contributing Factors field where “Unsafe Speed” is cited, and it is recommended to use the Driver Contributing Factors field for the most efficient searches. 1 – \(Yes\)

17 \| P a g e

0 – \(No\)

Vehicle Type \(reserved\) All Terrain Vehicle Bus / Large Van \(9 or more Seats\) Car/Station Wagon/Minivan Cargo Van \(10K lbs or less\) Light Truck w/Trailer Moped Motorcycle Other Other Pass Vehicle Other Truck Passenger Van \(&lt; 9 Seats\) Pedalcycle Pickup Recreation Vehicle Single Unit \(2 axle\) Single Unit \(3+ axle\) Single Unit Truck w/Trailer Sport Utility Vehicle Streetcar/Trolley Tractor Double Tractor Semi-Trailer Tractor Triple Truck Tractor \(Bobtail\) Unknown any previous w/ Trailer

Vertical Alignment – Roadway vertical alignment at crash location, as cited by reporting officer. Grade Hillcrest Level Unknown

Work\_Zone\_Related – Indicates if the crash took place within a Construction Zone, Utility Zone or Maintenance Zone. This is a count of crashes. This field is identical to the Crash Characteristics field where “Work Zone” is cited, and it is recommended to use the Crash Characteristics field for the most efficient searches. 1 – \(Yes\) 0 – \(No\)

18 \| P a g e

Young Driver Involved - At least one of the drivers involved was between the ages of 16 and 20 years of age. This is a count of crashes. This field is identical to the Crash Characteristics field where “Young Driver” is cited, and it is recommended to use the Crash Characteristics field for the most efficient searches. 1 – \(Yes\) 0 – \(No\)

### 

### 



