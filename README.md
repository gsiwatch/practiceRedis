# Redis knowledge base
[redis.io](https://redis.io/)

redis:

commands: 
1. redis-server
2. redis-cli: the client to connect to the redis server
3. info - to give the information related to redis
4. info clients: give the clients related information
5. info server: to give server related information
6. info memory: memory related stats
7. info stats: to get the stats
8. info replication: it has full capability of master slave replication- it gives information about it
9. info cpu: info about cpu
10. info cluster: multiple redis servers
11. info keyspace: 
12. quit: to quit the connection

Redis is No SQL in Memory Server

there is documentation about the commands too


what is redis cli: 


Caching is a process of storing some data in cache. Cache is a temporary storage component area where data is stored so that in future data can be get easily accessible 

cpu has registers - small amount of fast storage - they are the closest and also the fastest 

RAM - they are also closer to CPU but not as close as that of CPU

Hard disk drives - solid state drive - they will make access to the data faster 
Disk will remember the data

Caching is everywhere

Database selection:
Redis: if we need to in memory data and to be stored in key value pair
MongoDB/ Couch DB - if the clients have documents for example linkedin and they want to store the information
Cassandra - if the clients have wide column
Neo4j - if the client data is graph based for example social website


# About Redis
Redis - NoSQL in Memory Database, it is an open source database that is used to build highly scalable web performant applications. 
key value store

In Memory database: it is used for short lived data, it is often used with session, page hit counts. And use it when we do not care if we will loose some piece of data. It is super super fast and highly scalable.


