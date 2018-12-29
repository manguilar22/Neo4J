# Create Nodes & Relationships

#### Create Nodes
```cypher
CREATE(:Person{name:"...",age:0,weight:100})
CREATE(:Car{name:"...",make:"..."})
```

#### Create Relationships

```cypher
MATCH (p:Person), (c:Car)
WHERE p.name == "..." AND c.name == "..." AND c.make="..."
CREATE (p) -> [r:Drives] -> (c)
RETURN r
```
