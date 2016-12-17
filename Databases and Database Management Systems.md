# Databases and Database Management Systems

- Data Warehouse and Data Lake
    + [AWS Redshift](https://aws.amazon.com/documentation/redshift/) - Fast, simple, cost-effective data warehousing
    + [Google Cloud BigQuery](https://cloud.google.com/bigquery/docs/) - Fully managed, petabyte scale, low cost analytics data warehouse
    + [Apache Tajo](http://tajo.apache.org/docs/current/index.html) - A robust big data relational and distributed data warehouse system for Apache Hadoop
    + [Greenplum](http://gpdb.docs.pivotal.io/43100/common/welcome.html) - The World's First Open Source Massively Parallel Data Warehouse
    + [IBM Netazza](https://www-01.ibm.com/software/data/netezza/) - The Simple Data Warehouse Appliance for Serious Analytics
- NoSQL
    + Document
        + [MongoDB](https://docs.mongodb.com/) - NoSQL document store
        + [CouchBase](http://developer.couchbase.com/documentation-archive) - A document database with a SQL-based query language that is engineered to deliver performance at scale
        + [CouchDB](http://docs.couchdb.org/en/2.0.0/) - NoSQL document store
        + [AWS DynamoDB](https://aws.amazon.com/documentation/dynamodb/) - A fully managed NoSQL database service that provides fast and predictable performance with seamless scalability
        + [RethinkDB](https://rethinkdb.com/docs/) - RethinkDB is the open-source, scalable database that makes building realtime apps dramatically easier
        + [Azure's DocumentDB](https://docs.microsoft.com/en-us/azure/documentdb/) - A fully managed NoSQL database service built for fast and predictable performance, high availability, elastic scaling, global distribution, and ease of development
    + Column and wide-column (Big-table style)
        + [Google Cloud BigTable](https://cloud.google.com/bigtable/docs/) - Fast, fully managed, massively scalable NoSQL database service
        + [Apache Cassandra](http://cassandra.apache.org/doc/latest/) - Free and open-source distributed database management system designed to handle large amounts of data across many commodity servers, providing high availability with no single point of failure
        + [Druid](http://druid.io/docs/latest/design/index.html) - An open source data store designed for OLAP queries on event data
        + [HyperTable](http://www.hypertable.com/documentation/) - A high performance, open source, massively scalable database modeled after Bigtable
        + [Apache HBase](https://hbase.apache.org/book.html) - Apache HBase is the Hadoop database, a distributed, scalable, big data store
        + [AWS SimpleDB](https://aws.amazon.com/documentation/simpledb/) - A highly available, scalable, and flexible non-relational data store that enables you to store and query data items using web services requests
    + Key-value
        + [Redis](http://redis.io/documentation) - An open source (BSD licensed), in-memory data structure store, used as database, cache and message broker
        + [Apache Accumulo](https://accumulo.apache.org/) - A sorted, distributed key/value store that provides robust, scalable data storage and retrieval
        + [Memcache](https://memcached.org/) - High-performance, distributed memory object caching system
        + [Riak](https://docs.basho.com/) - Distributed NoSQL Database
        + [AWS DynamoDB](https://aws.amazon.com/documentation/dynamodb/) - A fully managed NoSQL database service that provides fast and predictable performance with seamless scalability
        + [Azure Table Storage (ATS)](https://docs.microsoft.com/en-us/azure/storage/)
    + Graph
        + [Neo4j](https://neo4j.com/docs/) - World's fastest and most scalable graph database
        + [Titan](https://github.com/thinkaurelius/titan) - A highly scalable graph database optimized for storing and querying large graphs with billions of vertices and edges distributed across a multi-machine cluster
        * [OrientDB](http://orientdb.com/docs/last/) - A document-graph database, meaning it has full native graph capabilities coupled with features normally only found in document databases
- RDBMS
    - [AWS RDS](https://aws.amazon.com/documentation/rds/) - Amazon Relational Database Service
        + [AWS Aurora](https://aws.amazon.com/rds/aurora/getting-started/) - MySQL-compatible relational database with 5X performance
        + [Oracle](https://docs.oracle.com/en/database/)
        + [Microsoft SQL Server](https://msdn.microsoft.com/en-us/library/mt590198(v=sql.1).aspx)
        + [PostgreSQL](https://www.postgresql.org/docs/)
        + [MySQL](https://dev.mysql.com/doc/)
        + [MariaDB](https://mariadb.org/learn/)
    + [MySQL](https://dev.mysql.com/doc/) - Open source RDBMS
    + [PostgreSQL](https://www.postgresql.org/docs/) - Open-source Object-Relational DBMS supporting almost all SQL constructs
    + [SQLite](https://www.sqlite.org/docs.html) - A self-contained, high-reliability, embedded, full-featured, public-domain, SQL database engine
    + [Apache Kudu](https://kudu.apache.org/docs/) - A columnar storage manager developed for the Hadoop platform
    + [Oracle Database](http://www.oracle.com/technetwork/database/index.html)
    + [Microsoft SQL Server](https://msdn.microsoft.com/en-us/library/mt590198(v=sql.1).aspx)
- In-memory
    + [VoltDB](https://docs.voltdb.com/?utm_source=LL-UX&utm_medium=resources-dropdown&utm_content=resources-dropdown-top&utm_campaign=docs) - The only in-memory, operational database purpose-built to help businesses build high velocity applications
    + [MemSQL](http://docs.memsql.com/docs) - A high-performance, in-memory database that combines
    + [SAP HANA](https://hcp.sap.com/index.html#) - An open platform-as-a-service that provides unique in-memory database and application services
the horizontal scalability of distributed systems with the familiarity of SQL
- Static storage
    - [AWS S3](https://aws.amazon.com/documentation/s3/) - Simple, durable, massively scalable object storage
- Search and full-text
    - [ElasticSearch](https://www.elastic.co/guide/index.html) - Service that makes it easy to deploy, operate, and scale Elasticsearch in the AWS Cloud
    - [Apache Lucene](https://lucene.apache.org/core/documentation.html) - Java-based indexing and search technology, as well as spellchecking, hit highlighting and advanced analysis/tokenization capabilities
    - [Apache Solr](http://lucene.apache.org/solr/resources.html#documentation) - A high performance search server built using Lucene Core, with XML/HTTP and JSON/Python/Ruby APIs, hit highlighting, faceted search, caching, replication, and a web admin interface
    - [Apache PyLucene](http://lucene.apache.org/pylucene/features.html) - A Python port of the Lucene Core project
- Cache
    - [Memcache](https://memcached.org/) - High-performance, distributed memory object caching system
    - [Redis](http://redis.io/documentation) - An open source (BSD licensed), in-memory data structure store, used as database, cache and message broker
- Time-series and event data
    + [InfluxDB](https://docs.influxdata.com/influxdb/v1.1/) - A time series database built from the ground up to handle high write and query loads
    + [Prometheus](https://prometheus.io/docs/introduction/overview/) - An open-source systems monitoring and alerting toolkit originally built at SoundCloud
    + [Druid](http://druid.io/docs/0.9.1.1/design/index.html) - An open source data store designed for OLAP queries on event data
    + [Geras](http://1248.io/geras.php) - 
    + [KairosDB](https://github.com/kairosdb/kairosdb) - 
    + [kdb+](http://kx.com/resources.php) - 
    + [OpenTSDB](http://opentsdb.net/) - 
    + [TempoIQ](https://www.tempoiq.com/) - 