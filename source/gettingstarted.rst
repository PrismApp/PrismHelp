Getting started with Prism:
===========================

You can quickly create and modify graphs using Prism’s interactive interface. you need not to install Prism to use it. You simply need to Login into "http://sandbox.relevancelab.com/SPECTRA/login?app=ROLE_PRISM" in a browser.

.. image:: /images/login.png

Once you will login to Prism you will be at **Data Analyser's** screen from where you can Select source for Analytics

.. image:: /images/home.png

You will be having 5 sources for data analytics:

1. HIVE: table stored in hadoop

2. PostgreSQL: table stored in postgreSQL

3. Excel: you can upload excel file

4. Web service: rest web services

5. My Saved Profiles: profiles designed by you

Select any one of the above, for instance click on HIVE, you will be navigate to- select database and table page:

.. image:: /images/01.png

select database and table from the dropdown and click on proceed button:

.. image:: /images/02.png

By clicking on proceed button you will be on the screen from where you can start drawing your charts

.. image:: /images/03.png

Here, you have different sections from where you can specify and can draw the graph. We have 5 sections in the page which are:

1. Dimensions

2. Filters

3. Measures

4. Notification Date

5. Profile View

You can drag any dimension and measure from the Dimensions and Measures section in Profile View section to draw the graph

.. image:: /images/04.png

Click on the graph lable, you can specify the type of the chart and can edit the properties of the graph. Bydefault type of the chart would be **Pie**

.. image:: /images/05.png

Select chart type to **Bar** and click on Save button. and click on Preview Button

.. image:: /images/06.png

******

Filter
======

To put some filter on the graph we have some option in the filter section, which are:

* Field: Select any field from dropdown on which you want to apply filter.

* Display Name: which you want to display for filtration of the data.

* Type: type of the data could be Text, Date, Dynamic date, Number, look Up and Drop Down.

* Default Value: you can put some default value for filter.

* Look Up Query: you can filter data on some query.

* Invisible: invisible -> off that means filter would be visible.

* Mandatory: you can add some mandatory field for filter the data.

* Add: we can add another field for filter.

* Select Type: select type could be single or multiple.

* Search Type: Search type could be In, Not In, Like and Not Like.

* Show Type: It will show search type in the filter screen.

.. image:: /images/filter.png



How to create a table
=====================

By clicking on **Add Table** button, you can have the table.

.. image:: /images/createTable01.png

Now, click on **Edit Title** button 

.. image:: /images/createTable02.png

Here you can edit the table:

* Title: Edit the table name

* Callback on cell click: Popup will display on click of particular cell.

* OrderBy: you can arrange the table data by setting its index value, and index starts with 0.

* Type: **DESC** and **ASC**. You can arrange data on ascending or descending basis.

* Widget width: you can edit table width to 25%, 50%, 75% or 100%.

* Render Type: 2 types of render type:

	* Server Side: We request to the server for data.

	* Client Side: All of the data is fetched in one go.

* Change table: Bydefault it will show selected table, but you can select any other table from drop down.

* Default Filter applied on Data Table: Whatever default filter you want to apply in your table you can put here.

* Edit Type: There are 2 types available to edit the table data:

	* Inline: You can edit by clicking on a particular cell.

	* Form: In From Edit Type, it will open a popup to edit the table.

* Fixed Left Columns: If your table is wide enogh that you have to scroll it to access the table and you want some particular colunm to visible while scrolling. fix any number of left colunm of the table to the screen.

* Fixed Right Columns: fix any number of right colunm of the table to the screen.

* Table Editable: By setting yes/no you can make your table editable. You can find editable table in PostgreSQL.

* Enable Audit Log: It will record all the activity log of the table as what is updated, who changed it and at what time.  

* Show Audit Log: If you will enable this button then it will show the audit log.

* Column Info: If you will click on **info** icon then it will show all the information about colunm throgh charts.

* Configure Actions: In this section we can define buttons as we wanted in our table, bydefault we will have excel and CSV buttons. The button could be visible inline and dropdown, and could be of any type - Default, primary, success etc, and we can have any number of buttons.

Action title, we can write button name
Callback function on Action, we can write function to perform some action.


**Configure**: Click on configure button of the Data Table, one popup will open:

.. image:: /images/configure01.png

* Column Settings: We have two sections **Available Columns** and **Selected Columns**. By default all the columns would be under Selected Columns, from there we can move columns to Available Columns using Add & Remove buttons and we can keep selected columns to show in the table. Click on any Selected column you will get few option to perform on that column:

.. image:: /images/configure02.png

* Field: Column Name which you selected

* Display Name: You can edit any field name by updating display name

* Width: We can specify the width of a perticular column

* Class: You can add javascript here for the field.

* Aggregate: To get the aggregate of a perticular column we can select any one from the drop down: None, SUM, COUNT, Distinct, AVG.

* Summary Type: If you want some summary on the column you can select one from the drop down: None, SUM, COUNT, Distinct, AVG

* Render Function: [{"id":"1","text":"HR"},{"id":"2","text":"IT"}]

* Invisible: If you will click yes for this then the column will not be visible in the table but the column will be searchable.

* Mandatory: You can make any field in the table as mandatory.

* Primary Key: You can set any column as a primary key for the table.

* Editable: You can make any field editable in the table.

* Edit Type: If you will make any field as editable then you can specify its edit type as Text, Text Area, Select, Checkbox, Date, Lookup and Number.

* Select Option / Lookup Query: You can specify your select query here like **select username,'' from users where lower(username) like '%<Q>%'**.

*****

Summary
=======


