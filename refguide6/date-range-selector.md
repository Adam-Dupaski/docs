---
title: "Date Range Selector"
space: "Reference Guide 6"
parent: "report-widgets"
---

<div class="alert alert-info">{% markdown %}

This has been renamed to [Report Date Parameter](report-date-parameter) in version 6.10.0.

{% endmarkdown %}</div>

With a date range selector the end user can filter a report on a parameter of the data set which has type DataTime.

In the date range selector you can add [date range fields](date-range-field) to make it easier for an end user to select a data range. (This can be done by right clicking the data range selector and choosing add field from the popup menu.)

## Appearance Properties

### Fields per row

This property indicates how many date range fields can be placed beside each other in a row. (There are always two rows available for data range fields.)

### From label

Text that's displayed beside the place where an end user can choose **from** which date/time occurrences should be shown in the report.

### To label

Text that's displayed beside the place where an end user can choose **to** which date/time occurrences should be shown in the report.

## Behavior Properties

### Show from/to

True if fields in which the user can fill in from and to when results should be shown in the report.

False if these fields are not shown, and the filter is thus determined by the date range fields in this date range selector.

### Min. year

Minimum year which can be chosen in a date range field in which the end user can choose a year.

### Max. year

Maximum year which can be chosen in a date range field in which the end user can choose a year.

### Parameter

Parameter of the data set of which the range is determined by this date range selector.

## Common Properties

### Name, Class, Style

See [Widget Properties](common-widget-properties).
