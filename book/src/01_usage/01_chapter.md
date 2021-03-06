# User Guide

This guide describes the most common usecases for using chipmunk.

## Searching and Filtering

<img src="../images/magnifying-search-lenses-tool.png" width="100" height="100">

Searching through huge logfiles

## Concatenating logfiles

<img src="../images/glue_together.png" width="100" height="100">

`chipmunk` can combine multiple log file. This is useful for example
when you just want to reassamble a logfile that were stored in parts.

## merging

![](../images/intersection.png)

Merging is useful if you have several log files e.g. from different
devices/processors and you want combine them by merging according to their
timestamps.

## Charts

![](../images/chart.png)

To better understand what's going on in a large logfile, it can be helpful to visualize data over
time. `chipmunk` let's you define regular expressions that match a number and to use this expression
to capture a value throughout a logfile.

## Bookmarks

<img src="../images/bookmark_sign.png" width="100" height="100">

Add bookmarks to mark and remember important log entries. Jump between bookmarks with shortcuts (`j` and `k`).

## DLT - Diagnostic Log and Trace

<img src="../images/dlt.png" width="200" height="200">

View and search and filter DLT files.
rogramming in Rust!
