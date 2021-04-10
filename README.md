# DSN analysis and data visualization
## Analysis of Developer Social Network, Contribution Patterns and Link to Bug fixes

This project is an analysis using a case study gitlab project: Tiki Project
+ It produces results from Data (log) extraction and collection, Data clean-up, Data Categorization, Data Visualisation of developer contributions to the project.
+ I use Leiden Algorithm and temporal network parameters by defining edge data with source, target, and unique identifiers to view the contibution in different time snapshots.
+ Overall, this result show a supervised machine learning model and pattern useful for network groupings and developer recommendation for bug fixes

- [Data Extraction](#data-extraction)
- [Data Categorization](#data-categorization)
- [Data Visualization](#data-visualization)


![DSN visualization result](https://github.com/Edwin-programmer/DSN-analysis-data-visualization/blob/main/DSN%20files/Grouping%20result.png)
### Data Extraction
The data is then extracted from the local Git repository using the GitExtractor. 
+ Once extracted, a GitExtractor method can be called to return data in a Pandas DataFrame.
![DSN visualization result](https://github.com/Edwin-programmer/DSN-analysis-data-visualization/blob/main/DSN%20files/extract1.jpg)
![DSN visualization result](https://github.com/Edwin-programmer/DSN-analysis-data-visualization/blob/main/DSN%20files/extract2.jpg)
### Data Categorization
![DSN visualization result](https://github.com/Edwin-programmer/DSN-analysis-data-visualization/blob/main/DSN%20files/edge1.jpg)
### Data Visualization
Overall, the network comprises of 174 Nodes and 28021 Edges. 
+ The thickness of the edge represent the contribution weight and the red nodes represent the bug related instances: [FIX], [ENH], [MOD], [REF], [NEW], [REL], [UPD], [KIL], [ADD], [SEC], [CSS], [UI], [SVN].
![DSN visualization result](https://github.com/Edwin-programmer/DSN-analysis-data-visualization/blob/main/DSN%20files/visualize1.jpg)
The sequence of contributions points out some key developers that have shown sustained contribution over time.
+ Temporal networks are network representations that flow through time. They give a view of the network as it develops over time, taking snapshots at a few key moments over the course of its timespan
![DSN visualization result](https://github.com/Edwin-programmer/DSN-analysis-data-visualization/blob/main/DSN%20files/visualize2.jpg)
![DSN visualization result](https://github.com/Edwin-programmer/DSN-analysis-data-visualization/blob/main/DSN%20files/visualize3.jpg)
