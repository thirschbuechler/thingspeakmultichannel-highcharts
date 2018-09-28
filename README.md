thingspeakmultichannel-highcharts
=================================

Multichannel display from Thingspeak.com using Highcharts.com. 
 by turgo initially released at 
 http://forum.arduino.cc/index.php?topic=213058.msg1560990#msg1560990
 
 Displays multiple channels of data and fields, using Highchart.com, from a thingspeak.com channels.
 
 Features:
 - cursor click (vertical rectangle, kind of) on chart to zoom y-axis
 - top left buttons to select range of data, or use timeline below chart
 - top right 3 bars ("burger menu") to download data as picture/pdf/csv/xls
 - hide/show all or certain traces
 - auto-load new data (if righthand-side of graph set to last values and checkbox checked)
 - load single/all channels from thingspeak which are connected
 
 The data will be averaged if it's too dense to display after a certain zoom-out level,
 gaps in data are always connected by a straight line.
 
