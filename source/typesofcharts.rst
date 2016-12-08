Types of Charts
===============

There are 20 types of charts available, which are:

1. Pie Chart

2. Donut Chart

3. Bar Chart

4. Row Chart

5. Timeline Chart

6. Line Chart

7. Stacked bar Chart

8. Grouped bar Chart

9. Paired Row

10. Multi level

11. Geo

12. Google Map

13. Bubble

14. Heat Map

15. Distribution

16. Composite

17. Hierarchie

18. Range Slider

19. Scatter Plot

20. series


Pie Chart
^^^^^^^^^

A pie chart is a circular statistical graphic, which is divided into sectors that each represent a proportion of the whole.

  .. image:: /images/piechart.png

Edit Properties:

Calculated Formula: Apllied only when aggregate is Calculated field ex:value1/(Value1-Value2)

Chart Title: Title of the chart

Width: Width of the chart

Height: Height of the chart

Tool Tip Key: We can define tooltip key in 3 ways: Code, Description, Code And Description. whether we want to display Code, Description, Code And Description in the tool tip key

Measure: In Measure we have all the fields available in the table and we can select any one from the drop down for which we want the summary.

Aggregate: We hve aggregate function like Sum, Count, AVG, Calculated Field, MIN, MAX, MEDIAN, DISTINCT and RATIO to get measure

Convert to Absolute ?: Convert value of each group the absolute value before plotting, we have 2 options Yes/No

Dimension description: Select field to display name of dimension in tooltip

  .. image:: /images/piechartDD.png


Measure Labels: format {"field1":"Display Name1","field2":"Display Name2"}

Sort Order: To sort the data we have few optiions: None(Data Source Order), Ascending, Alphabetic(A-Z), Alphabetic(Z-A) and Descending. By default None would be selected which has data source order

Show Percentage: Show Percentage in pop up, we have 2 options Yes/No wheter you want to show the percentage or not. Here we are showing data in percentage

  .. image:: /images/piechartpercentage.png


Number Format: Number Format is, in which format we want to display the number like .0F

  .. image:: /images/piechartNF.png

Prefix:  We can add some prefix

Suffix: We can add some suffix

Color Type: color typr could be of- By Category, Value Range, Single Color and Field. To set any Color type we need to set some color code

Color Codes: Here we can specify the color codes. Ex: by - Category {"US01":"","US02":"Line","US03":"AVG"}

Color Field: We can set any color field from the drop down

X Axis Title: We can add some title

Y Axis Title: We can add some title

X Axis Label Orientation:

Y Axis Label Orientation:

Default selected value(s): We can select some default selected value in the chart like A10

  .. image:: /images/piechartDSV.png


Link Actions: Linking Actions to Chart tooltip. we need to create action and that action we need to configure in pie chart and then it will be accessible in the Link Action field from where we can select Action

  .. image:: /images/piechartLA.png


Filter Field:

Filter Value:

Top/Bottom -N Filter: Calculation Type:

Filter:N From, We have two options Top and Bottom. If we will select Top it will show 20 from the top of table and if we will select Bottom it will show 20 from the Bottom of table

Filter-N: Default N- value: Here we have to pass some numeric value, It will return the number of rows whatever number we have passed.

Top/Bottom -N Filter: N-Values

Filter By: We can specify any field by which we want to filter the data.

Dynamic Dimension: We can add more than one dimention to the chart

  .. image:: /images/piechartDynamicD.png

*****

Donut Chart
^^^^^^^^^^^

A donut chart is essentially a Pie Chart with an area of the center cut out.

  .. image:: /images/donutchart.png
  

Calculated Formula: Apllied only when aggregate is Calculated field ex:value1/(Value1-Value2)
Chart Title	period:
Width: Width of the chart
Height: Height of the chart
Tool Tip Key: Code And Description	
Measure:
Aggregate: Aggregate Function
Convert to Absolute ?: Convert value of each group the absolute value before plotting
Dimension description: Select field to display name of dimension in tooltip
Measure Labels: format {"field1":"Display Name1","field2":"Display Name2"}
Sort Order: DESC- Descending by
Show Percentage: Show Percentage in pop up
Number Format:	
Prefix:
Suffix:
Color Type:	 	
Color Codes: Ex: by - Category {"US01":"","US02":"Line","US03":"AVG"},
Color Field:	 	
X Axis Title:	 	
Y Axis Title:	 	
X Axis Label Orientation:	0	
Y Axis Label Orientation:	0	
Default selected value(s):	 	
Link Actions: Linking Actions to Chart tooltip
Filter Field:	 	
Filter Value:	 	
Top/Bottom -N Filter: Calculation Type	None	
Filter:N From	Top	
Filter-N: Default N- value	 	
Top/Bottom -N Filter: N-Values	 	
Filter By:	
Dynamic Dimension:

*****

Bar Chart
^^^^^^^^^

  .. image:: /images/06.png


Calculated Formula: Apllied only when aggregate is Calculated field ex:value1/(Value1-Value2)
Chart Title	plant: 	
Width: Width of the chart
Height: Height of the chart
Tool Tip Key: Code And Description	
Measure:	
Measures:	 	
Aggregate	SUM	Aggregate Function
Convert to Absolute ?	 	Convert value of each group the absolute value before plotting
Dimension description	 	Select field to display name of dimension in tooltip
Measure Labels	 	format {"field1":"Display Name1","field2":"Display Name2"}
Sort Order	 	DESC- Descending by
Show Totals	Yes	
Show Percentage	 	Show Percentage in pop up
Number Format	 	
Prefix	 	
Bar Width	 	Width of the Bar
Suffix	 	
Color Type	 	
Color Codes	 	Ex: by - Category {"US01":"","US02":"Line","US03":"AVG"},
Color Field	 	
X Axis Title	 	
Y Axis Title	 	
X Axis Label Orientation	0	
Y Axis Label Orientation	0	
Top Margin	20	Space between top of the chart and top of the chart container (Pixels)
Right Margin	10	Space between right of the chart and right margin of the chart container (Pixels)
Bottom Margin	30	Space between X axis and bottom of the chart container (Pixels)
Left Margin	40	Space between Y axis and left margin of the chart container (Pixels)
Default selected value(s)	 	
Link Actions	 	Linking Actions to Chart tooltip
Filter Field	 	
Filter Value	 	
Top/Bottom -N Filter: Calculation Type	None	
Filter:N From	Top	
Filter-N: Default N- value	 	
Top/Bottom -N Filter: N-Values	 	
Filter By	 	
Dynamic Dimension

*****

Row Chart
^^^^^^^^^

  .. image:: /images/rowchart.png


Calculated Formula	 	Apllied only when aggregate is Calculated field ex:value1/(Value1-Value2)
Chart Title	plant	
Width	auto	Width of the chart
Height	auto	Height of the chart
Chart Container Height	 	
Measure	 	
Aggregate	SUM	Aggregate Function
Convert to Absolute ?	 	Convert value of each group the absolute value before plotting
Dimension description	 	Select field to display name of dimension in tooltip
Measure Labels	 	format {"field1":"Display Name1","field2":"Display Name2"}
Sort Order	 	DESC- Descending by
Show Totals	Yes	
Show Percentage	 	Show Percentage in pop up
Number Format	 	
Prefix	 	
Bar Width	 	Width of the Bar
Suffix	 	
Color Type	 	
Color Codes	 	Ex: by - Category {"US01":"","US02":"Line","US03":"AVG"},
Color Field	 	
X Axis Title	 	
Y Axis Title	 	
X Axis Label Orientation	0	
Y Axis Label Orientation	0	
Hide X Axis	 	
Hide Y Axis	 	
Top Margin	20	Space between top of the chart and top of the chart container (Pixels)
Right Margin	10	Space between right of the chart and right margin of the chart container (Pixels)
Bottom Margin	30	Space between X axis and bottom of the chart container (Pixels)
Left Margin	40	Space between Y axis and left margin of the chart container (Pixels)
Default selected value(s)	 	
Link Actions	 	Linking Actions to Chart tooltip
Filter Field	 	
Filter Value	 	
Top/Bottom -N Filter: Calculation Type	None	
Filter:N From	Top	
Filter-N: Default N- value	 	
Top/Bottom -N Filter: N-Values	 	
Filter By	 	
Dynamic Dimension

*****

Timeline Chart
^^^^^^^^^^^^^^

*****

Line Chart
^^^^^^^^^^

*****

Stacked bar Chart
^^^^^^^^^^^^^^^^^

*****

Grouped bar Chart
^^^^^^^^^^^^^^^^^

*****

Paired Row
^^^^^^^^^^

*****

Multi level
^^^^^^^^^^^

*****

Geo
^^^

*****

Google Map
^^^^^^^^^^

*****

Bubble
^^^^^^

*****

Heat Map
^^^^^^^^

*****

Distribution
^^^^^^^^^^^^

*****

Composite
^^^^^^^^^

*****

Hierarchie
^^^^^^^^^^

*****

Range Slider
^^^^^^^^^^^^

*****

Scatter Plot
^^^^^^^^^^^^

*****

series
^^^^^^

*****