pydate

A Python package made to format date & time strings for use in various SQL RDBMS.

Make sure to have the latest version of Python 3 installed although this should work with previous versions. 

To install the package with pip enter command in terminal:
    pip install pydate

To uninstall the package with pip enter command in terminal:
    pip uninstall pydate

-----------
Module Year
-----------

year: 	                        Attribute of the int type representing a year.
                                The attribute must be 4 digits.

get_year(): 	                Return the year attribute value.

set_year(year): 	            Change the year attribute value.

set_year_UTC():                 Change the year attribute to the current UTC year.

tostring(): 	                Return a string representing the Year class attribute values. 

-----------
Module Date
-----------

Note: This class inherits the attributes/methods of the Year class. 

month: 	                    Attribute of the int type representing a month.
                            The attribute's value must be between 1 & 12.

day: 	                    Attribute of the int type representing a day.
                            The attribute's value must be between 1 & 31.

get_month(): 	            Return the month attribute value.

get_day(): 	                Return the day attribute value.

get_gregorian():            Return the Gregorian month name.

get_total_days():           Return a dictionary denoting the total days in each month. 
                            Uses each gregorian month name as a key.

set_month(month): 	        Change the month attribute value.

set_month_UTC():            Change the month attribute to the current UTC month.

set_day(day): 	            Change the day attribute value.

set_day_UTC():              Change the day attribute to the current UTC day. 

tostring(): 	            Return a string representing the Date class attribute values.

-----------
Module Time
-----------

hour: 	                    Attribute of the int type representing a hour.
                            The attribute's value must be between 0 & 23.

minute: 	                Attribute of the int type representing a minute.
                            The attribute's value must be between 0 & 59.

second: 	                Attribute of the int type representing a second.
                            The attribute's value must be between 0 & 59.

get_hour(): 	            Return the hour attribute value.

get_minute(): 	            Return the minute attribute value.

get_second(): 	            Return the second attribute value.

set_hour(hour): 	        Change the hour attribute value.

set_hour_UTC():             Change the hour attribute to the current UTC hour.

set_minute(minute): 	    Change the minute attribute value.

set_minute_UTC():           Change the minute attribute to the current UTC minute.

set_second(second): 	    Change the second attribute value.

set_second_UTC():           Change the second attribute to the current UTC second. 

tostring(): 	            Return a string representing the Time class attribute values.

---------------
Module DateTime
---------------

Note: This class inherits the attributes/methods of both the Date & Time classes.

set_UTC():                  Change year, month, day, hour, minute, and second attributes to current UTC values.

set_EST():                  Change year, month, day, hour, minute, and second attributes to current EST values (UTC-05:00).

tostring(): 	            Return a string representing the DateTime class attribute values. 