# ***pydate***

    A Python package made to format date & time strings for use in various SQL RDBMS.

    Make sure to have the latest version of Python 3 installed although this should work with previous versions. 
    Pip and git also need to be installed for package installation with command line.  

    To install/update the package with pip enter command in terminal:
        pip install git+https://github.com/CodeConfidant/pydate-time.git#egg=pydate-time

    To uninstall the package with pip enter command in terminal:
        pip uninstall pydate

## ***Module Year***

<table width="100%">
	<tr>
		<th align="left">
            Attribute/Method
        </th>
		<th align="left">
            Description
        </th>
	</tr>
	<tr>
		<td>
            <code>year</code>
        </td>
		<td>
            Attribute of the int type representing a year. <br/>
            The attribute must be 4 digits.
        </td>
	</tr>
    <tr>
		<td>
            <code>get_year()</code>
        </td>
		<td>
            Return the year attribute value.
        </td>
	</tr>
    <tr>
		<td>
            <code>set_year(year)</code>
        </td>
		<td>
            Change the year attribute value.
        </td>
	</tr>
    <tr>
		<td>
            <code>tostring()</code>
        </td>
		<td>
            Return a string representing the Year class attribute values.
        </td>
	</tr>
</table>

---

## ***Module Date***

    Note: This class inherits the attributes/methods of the Year class. 

<table width="100%">
	<tr>
		<th align="left">
            Attribute/Method
        </th>
		<th align="left">
            Description
        </th>
	</tr>
	<tr>
		<td>
            <code>month</code>
        </td>
		<td>
            Attribute of the int type representing a month. <br/>
            The attribute's value must be between 1 & 12.
        </td>
	</tr>
    <tr>
		<td>
            <code>day</code>
        </td>
		<td>
            Attribute of the int type representing a day. <br/>
            The attribute's value must be between 1 & 31.
        </td>
	</tr>
    <tr>
		<td>
            <code>get_month()</code>
        </td>
		<td>
            Return the month attribute value.
        </td>
	</tr>
    <tr>
		<td>
            <code>get_day()</code>
        </td>
		<td>
            Return the day attribute value.
        </td>
	</tr>
    <tr>
		<td>
            <code>set_month(month)</code>
        </td>
		<td>
            Change the month attribute value.
        </td>
	</tr>
    <tr>
		<td>
            <code>set_day(day)</code>
        </td>
		<td>
            Change the day attribute value.
        </td>
	</tr>
    <tr>
		<td>
            <code>tostring()</code>
        </td>
		<td>
            Return a string representing the Date class attribute values.
        </td>
	</tr>
</table>

---

## ***Module Time***

<table width="100%">
	<tr>
		<th align="left">
            Attribute/Method
        </th>
		<th align="left">
            Description
        </th>
	</tr>
	<tr>
		<td>
            <code>hour</code>
        </td>
		<td>
            Attribute of the int type representing a hour. <br/>
            The attribute's value must be between 0 & 23.
        </td>
	</tr>
    <tr>
		<td>
            <code>minute</code>
        </td>
		<td>
            Attribute of the int type representing a minute. <br/>
            The attribute's value must be between 0 & 59.
        </td>
	</tr>
    <tr>
		<td>
            <code>second</code>
        </td>
		<td>
            Attribute of the int type representing a second. <br/>
            The attribute's value must be between 0 & 59.
        </td>
	</tr>
    <tr>
		<td>
            <code>get_hour()</code>
        </td>
		<td>
            Return the hour attribute value.
        </td>
	</tr>
    <tr>
		<td>
            <code>get_minute()</code>
        </td>
		<td>
            Return the minute attribute value.
        </td>
	</tr>
    <tr>
		<td>
            <code>get_second()</code>
        </td>
		<td>
            Return the second attribute value.
        </td>
	</tr>
    <tr>
		<td>
            <code>set_hour(hour)</code>
        </td>
		<td>
            Change the hour attribute value.
        </td>
	</tr>
    <tr>
		<td>
            <code>set_minute(minute)</code>
        </td>
		<td>
            Change the minute attribute value.
        </td>
	</tr>
    <tr>
		<td>
            <code>set_second(second)</code>
        </td>
		<td>
            Change the second attribute value.
        </td>
	</tr>
    <tr>
		<td>
            <code>tostring()</code>
        </td>
		<td>
            Return a string representing the Time class attribute values.
        </td>
	</tr>
</table>

---

## ***Module DateTime***

    Note: This class inherits the attributes/methods of both the Date & Time classes.

<table width="100%">
	<tr>
		<th align="left">
            Method
        </th>
		<th align="left">
            Description
        </th>
	</tr>
	<tr>
		<td>
            <code>tostring()</code>
        </td>
		<td>
            Return a string representing the DateTime class attribute values.
        </td>
	</tr>
</table>

[Back to Top](#pydate)

---
