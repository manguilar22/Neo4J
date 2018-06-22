# Neo4J_Graph

![](https://github.com/manguilar22/Neo4J_Graph/blob/master/images/neo4j.svg =500x500)

Graph Databases are cool ...

### Neo4J on Docker

![](https://github.com/manguilar22/Neo4J_Graph/blob/master/images/docker.svg =250x250)

``` bash
mkdir neo4j; mkdir data logs; cd neo4j
sudo docker run --name neo4j_server \
  --publish 4717:4717 \
  -v /data/:/data/ \
  -v /logs/:logs/ \
  neo4j:latest
```
