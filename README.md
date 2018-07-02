# Neo4J_Graph

<img src="https://github.com/manguilar22/Neo4J_Graph/blob/master/images/neo4j.svg" width="150px" height="100px"/>

Graph Databases are cool ...

##### Starting the Server

<img src="https://github.com/manguilar22/Neo4J_Graph/blob/master/images/Start_Neo4_J_Server.png" width="200" height="200"/>

##### Simple Connection 

<img src="https://github.com/manguilar22/Neo4J_Graph/blob/master/images/Example_Of_Possibilities.png" width="300" height="300"/>

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
