# [MongoDB Introduction](https://www.mongodb.com/docs/manual/introduction/)

1. Document Database  
A record in MongoDB is a document, which is a data structure composed of field and value pairs. Values of fields may include other documents, arrays and arrays of documents.

![Document similar to JSON](https://github.com/brianpsw/NoSQL/assets/85924543/1e5f21de-c1af-4269-8d7a-47f15b82e68a)


2. Advantages of using documents
   
    a. Can easily used in many programming languages
      
    b. Embedded documents and arrays reduce need for expensive joins  
      
    c. Dynamic schema supports fluent polymorphism  

4. Collections  
MongoDB stores documents in collections. (Table in RDB)

5. Key Features   
   
    a. High Performance
    Support for embedded data models => reduce I/O activity
    Indexes (Faster queries)
    
    b. Support CRUD / Data Aggregation / Text Search / Geospatial Queries
    
    c. High Availability
    Replica set
    
    d. Horizontal Scalability
    Sharding / Zones
    
    e. Support for Multiple Storage Engines
    WiredTiger Storage Engine / In-Memory Storage Engine / pluggable storage engine API

