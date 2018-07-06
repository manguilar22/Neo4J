# Neo4J_Graph

<img src="https://github.com/manguilar22/Neo4J_Graph/blob/master/images/neo4j.svg" width="150px" height="100px"/>

* __Nodes__ Entity Information 
* __Relationships__ Connect one node to another
* __Properties__ Nodes & Relationships are **containers** for properties
* __Labels__ to make subgraphs

##### Graph 

<img src="https://github.com/manguilar22/Neo4J_Graph/blob/master/images/Example_Of_Graph.svg" width="" height=""/>


##### Graph

<img src="https://github.com/manguilar22/Neo4J_Graph/blob/master/images/Find_Tom_Hanks.svg" width="" height=""/> 

### Neo4J on Docker

<img src="https://github.com/manguilar22/Neo4J_Graph/blob/master/images/docker.svg" width="150px" height="100px"/>

``` bash
mkdir neo4j; mkdir data logs; cd neo4j
sudo docker run --name neo4j_server \
  --publish 7474:7474 \
  --publish 7687:7687 \
  -v /data/:/data/ \
  -v /logs/:logs/ \
  neo4j:latest
```
