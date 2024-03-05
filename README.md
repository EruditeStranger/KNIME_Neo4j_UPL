# Pipeline for dynamically creating Neo4j graphs from CSV files.
A really cool project I did with UPL 4 years ago. Documentation in progress, more details to come soon!

## Extraction pipeline:
Signals Electronic Lab Notebook -> Unstructured data -> structured data in CSV files 
Once the data was structured, Reed and I spent nearly two months creating this bad boy
<br>

![High Level Architecture](Neo4j/KNIME_vhigh.png)

Confusing, eh? Let's dig deeper and break it down

## Setting the groundwork to create the knowledge graph's nodes
![CSV Files to Neo4j nodes](Neo4j/Extract.png)

## Creating the Neo4j Nodes

![Node Creation](Neo4j/Creating_Nodes.png)

## Creating the relationships

![Creating Relationships](Neo4j/Creating_Relationships.png)

## Analytics and graph query pipeline

![Queries](Neo4j/Analytics.png)

## Selecting Property values for nodes and relationships in the adjacency table
![Properties](Neo4j/Adjacency_Tables_Properties.png)

