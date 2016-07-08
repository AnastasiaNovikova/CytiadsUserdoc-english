.. _statistics-filter-label:

======
Filter
======

The filter in the **Statistics** manages the contents of the reports. The combination of the configured conditions in the **Filter** is a global condition for all reports in the **Statistics**. It means that the conditions stay the same as you navigate between the reports. 

.. figure:: ../../img/statistics/global_filter0.png
   :scale: 100 %
   :align: center
   :alt: Kalendar in the statistics

It works in the same way as other filters in our interface, but the statistics **Filter** has its peculiarities:

#. 1.	The reports will not be created without the :ref:`Period <statistics-calendar-label>` filter. It means that you have to specify the date, for which you want to see the statistics.
#. 2.	You can set the condition *exclude* for the **Statistics** filters.

   For example, to display the statistics on all offers, except **003.RU**:
   
   #. Open the filter by offers.
   #. Check **All**.
   #. Uncheck the offer **003.RU**.
   #. Click  :guilabel:`Apply`.

#. 3.	To rebuild the report using the filter, click :guilabel:`Apply`. 
#. 4.	If you click :guilabel:`Reset`, all previously set conditions will be deleted. The :ref:`Period <statistics-calendar-label>` condition will get its default value of **30 days**.

.. _statistics-calendar-label:

******
Period
******

The period you set in the :ref:`Filter <statistics-filter-label>`, will be applied to all your reports. Till you change it manually. To set the period, we have created the **Calendar**:

.. figure:: ../../img/statistics/calendar0.png
   :scale: 65 %
   :align: center
   :alt: Calendar in statistics
 
In the **Calendar** , you set the period, for which the statistics will be displayed. You can:

#. Select the date by clicking the calendar. Here you select the absolute date. It means that it will be saved as you set it. Tomorrow, the day after tomorrow and in a month you will see the statistics for the dates you have selected.
#. 2.	Select the period from the suggested ones (a day, 7 days, 30 days, etc.). Here you select the relative period. It means that each period will be counted from the current date.

   For example, you have selected 7 days. If you look at the statistics today, the data will be displayed for the last seven days. If you look at the statistics tomorrow, the period will be counted from tomorrow and include the last seven days

#. Enter the date manually. This date is also absolute (see the explanation in Item 1).
#. You can also use the **Compare** feature to see the statistics on two selected periods at the same time. You can select the period for comparison from the ones suggested earlier.
#. Or specify the period for comparison manually.

**********
My Reports
**********

НOf course, you have your favorite combinations of the :ref:`Filter  <statistics-filter-label>`, conditions that are used often. For example, you often analyze your traffic in Russia for the last week. In order not to perform the same settings every time, we have added the feature that allows to save your favorite reports. 

You can save as many reports as you want. All of them will be displayed in :menuselection:`Statistics | My Reports`.To view the saved report, just click it.

.. _statistics-save-label:

Save Report
===========

 .. figure:: ../../img/statistics/save_my_filter0.png
    :scale: 100 %
    :align: center
    :alt: Save statistics report

.. tip:: When you configure and save :ref:`Filters <statistics-filter-label>` using the **Save Report** function, in addition to the **Filters**, the report where you have saved the filter will be also saved. Therefore, we recommend to select the most convenient report for each filter to be saved.
 
To save your favorite combination of filters once:

#. Go to the report you use most often for the traffic analysis.
#. You can also set up the **Optional parameter**, и **Dinamics** and :ref:`the type of event date <onversion-download-label>`, if required; these parameters will be also saved.
#. Set up the conditions: period in the calendar and selection by filters.
#. Click the :guilabel:`Save report`button, then name the filter you are saving.
#. The report that you have just saved will appear in the :menuselection:`My Reports`.
