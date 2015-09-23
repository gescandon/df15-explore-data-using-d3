# df15-explore-d3
Explore Data Distributions using D3.js - DF15 Devzone

# slideshare
http://www.slideshare.net/armadillovoom/explore-data-distributions-using-d3js

#VF Page Descriptions

The following pages should work with a fresh SFDC Dev org (except where noted).

## d3AccountHierarchy
* Enhance the standard Account Hierarchy with this page. 
* Based on Collapsible Indented Tree : http://bl.ocks.org/mbostock/1093025.
* A simple conversion of hierarchical records into d3 formatted JSON. 

## d3AccountHierarchyColor2
* Enhance the standard Account Hierarchy with this page. 
* Based on Collapsible Indented Tree : http://bl.ocks.org/mbostock/1093025.
* A simple conversion of hierarchical records into d3 formatted JSON. 
* A different color scheme than d3AccountHierarchy.

## d3AccountSunburst
* Based on d3.js Sunburst: http://bl.ocks.org/mbostock/4063423
* A simple conversion of hierarchical records into d3 formatted JSON. 
* Looks cool, but not sure how valuable this is 0_o

## d3OpptyPartition
* Converts Parent/Child records into h3 formatted JSON.
* Based on Partition Table: http://mbostock.github.io/d3/talk/20111018/partition.html
* Element size based on aggregate Amount of Opportunities.

## d3OpptyPartition2
* Converts Parent/Child records into h3 formatted JSON.
* Based on Partition Table: http://mbostock.github.io/d3/talk/20111018/partition.html
* Element size based on number of children.


## d3TerritoryPartition
* Based on Partition Table: http://mbostock.github.io/d3/talk/20111018/partition.html
* More efficient conversion of hierarchical records into d3 formatted JSON.
* Handle large data sets better! >10k records 
* Limits depth of visualization.
* Uses an additional js file which provide mock csv data.
