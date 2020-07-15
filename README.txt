# Network-Gephi
Analyse the Apple website interact with other websites.<br />

The objective of this Project is to develop a visualize and analyze large networks using Gephi. This project focuses on the relationship between websites. Here we would be emphasizing on the association of Apple with other websites and with itself. 

I used Gephi, Gephi is an open source software for network visualization. It can read many file formats including Gephi, GEXF, GML, GDF, CSV and many others

Before starting with Gephi, we should familiarize ourselves with 2 terms, one being the Node & the other Edge.

Node: A node is a unique identifier of an object within a data set.
Edge: An edge is a line that connects two nodes
In order to import data from excel or csv file into Gephi, you will usually need to prepare following 2 files: <br />
* Node File – Containing the nodes and its attributes  <br />
    * The node file must include a column having name ‘ID’ <br />
    * ID column should contain unique entries <br />
* Edge File – Containing the edges and its attributes <br />
    * The edge file must include columns with name ‘Source’ & ‘Target’ which contains the start and the end nodes for each edge <br />


Steps: <br />
Create nodes and their relationships <br />
Create relationship strength between 2 nodes. <br />
Clustering based on websites (algorithm Fruchterman Reingold ) <br />
Clustering based on Industry (algorithm Yifan Hu ) <br />
Clustering based on Internal or External Linkage (algorithm Yifan Hu Proportional) <br />
