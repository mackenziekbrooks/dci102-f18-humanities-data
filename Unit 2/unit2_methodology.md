  # Unit 2 / Network / Methodology
Networks are everywhere. Once you start, it's hard to stop seeing them. The internet is a network, Facebook is a network, [Kevin Bacon is the central node](https://en.wikipedia.org/wiki/Six_Degrees_of_Kevin_Bacon) in the Hollywood network. Studying the connections between people and things is a major activity in the humanities, so "network analysis" feels like a natural method for working with humanities data. 

As we saw in Unit 1, we certainly *can* take statistical and mathematical methods and apply them to humanities data. As we learn about network analysis in this unit, we will consider whether or not we *should* use it with our data.

 
## Defining methods
### Networks, nodes, and edges
A network is, as Scott Weingart [says](http://journalofdigitalhumanities.org/1-1/demystifying-networks-by-scott-weingart/), "stuff and relationships." One piece of "stuff" is a "node" and the relationship/connection between two pieces of "stuff" is an "edge." Nodes are also called points, vertices, or agents. 

### Network analysis
Network analysis varies by discipline, but originates from graph theory in mathematics. This is a simplification, but the idea is that one can measure the important nodes in a network by how many connections they have to other nodes and by the weight/significance of those connections. If you're math literate, you can read more on [Wikipedia](https://en.wikipedia.org/wiki/Network_science).

### Social network analysis
Social network analysis, or SNA, is used by social scientists to study groups of people, their relationships to each other, and their relationships to other networks. 

If you want to learn more, Prof. Jon Eastwood in Sociology teaches a course on social network analysis. 

### Network visualization
As Franco Moretti points out in "Network Theory, Plot Analysis," the visualization of networks can be more useful to the humanities scholar than formal network analysis. Even if one does not calculate node centrality, visualizing your data as a network can affect the way you interpret that data.

### Graph database
Usually when we talk about databases, we're talking about relational databases. Tables of data are linked by primary/foreign keys. For example, Wordpress creates separate tables (think spreadsheets) for your user info, your posts, and your comments. Relationships are formed by the columns that live in a row together. 

Graph databases privilege the relationships between units of information. Attributes can be given to the nodes and edges to provide more details.

## Tools
### Palladio
[Palladio](http://hdlab.stanford.edu/palladio/) is a data visualization tool created by Stanford's Humanities + Design Research Lab. It's a browser-based tool that accepts structured data and creates network, geospatial, and gallery visualizations. It's easy to use, but can crash under too much data. 

### Gephi
[Gephi](https://gephi.org/) is a robust network/graph visualization tool. It runs from your computer and can accept large data sets (though you will need some patience). Gephi has a lot of options for changing the appearance of your network via filters and layout. You can also generate statistics about graph density etc. Lots of tutorials [here](https://gephi.org/users/).

### Neo4j
[Neo4j](https://neo4j.com/) is a "graph database." The "community edition" is easy to install and runs locally in your browser. Neo4j is well-documented and has a great training tutorial. Having experience with query languages like SQL will help with the learning curve. 

### Cytoscape
http://www.cytoscape.org/
[Tutorial by Miriam Posner](https://github.com/miriamposner/cytoscape_tutorials)

## Resources
### Programming Historian lessons
* [Reshaping JSON with jq](http://programminghistorian.org/lessons/json-and-jq)
* [From Hermeneutics to Data to Networks: Data Extraction and Network Visualization of Historical Sources](http://programminghistorian.org/lessons/creating-network-diagrams-from-historical-sources)

### Other
* [Creating a Network Graph with Gephi - Miriam Posner](http://miriamposner.com/dh101f14/?p=1389)
* [Two-mode Netorks - Tore Opsahl](https://toreopsahl.com/tnet/two-mode-networks/)
* [GEPHI – Introduction to Network Analysis and Visualization](http://www.martingrandjean.ch/gephi-introduction/)