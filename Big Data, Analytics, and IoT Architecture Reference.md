# Big Data, Analytics, and IoT Architecture Reference

## Reference Architectures
+ Extended Relational
+ Non-Relational
+ Hybrid

## Maturity Considerations - Oracle
- Reference architecture
- Development patterns
- Operational processes
- Governance structures and polices

## Normalization
- Minimum requirements
    + First Normal Form (1NF)
    + Third Normal Form (3NF)

## Goals and Deliverables
+ Business-level goals
    * Increase revenue
    * Increase profit
    * Decrease costs
    * Predict and/or reduce risk
    * Increase operational efficiency
    * Reduce waste
    * Increase customer acquisition, retention, and growth
    * Improve customer service
    * Enhance business development
    * Improve business governance
    * Drive data and evidence-driven decisions
    * Improve business agility
    * Decision management and inform decisions
    * Drive new business models
    * Discover new products and services
    * Business reporting and analysis
+ Real time intelligence and analytics
+ Security intelligence (security, fraud, and risk analysis)
+ Self-service (ad-hoc)
+ Personalize customer experiences
+ Stream computing
    * Event and data streams
+ Advanced analytics, data mining, data modeling, business intelligence (BI), statistical analysis, dashboards and reporting, enterprise performance management (EPM), information discovery
    * Data and insights discovery and exploration
    * Discover relevant trends and patterns
    * Descriptive analytics - What happened and why?
    * Predictive analytics - What is the probability of something happening?
    * Prescriptive analytics - What specific recommendations will drive business decisions and help achieve business goals (i.e., what to do if 'X' happens)
    * Query and reporting
    * OLAP Cubes
    * Advanced analytics
    * MapReduce
    * Search engines

## Architectural Goals, Principles, and Considerations
- Consistency
- Batch vs. real-time streaming data processing
    + Batch MapReduce via Hadoop
    + Real-time in-memory MapReduce via Spark
- Embedded models or interfaces
- API or RPC or REST
- Deployed trained models (offline learning) vs. [online learning](https://en.wikipedia.org/wiki/Online_machine_learning)
+ Latency (near real time)
+ Reliability and fault tolerance
+ Availability
+ Scalability/Volume handling
+ Performance/speed
    * Goals and implementation - Oracle
        - Analyze and transform data in real-time
        - Optimize data structures for intended use
        - Use parallel processing
        - Increase hardware and memory
        - Database configuration and operations
        - Dedicate hardware sandboxes
        - Analyze data at rest, in-place
+ Throughput
+ Extensibility
+ Security
+ Cost/financial
+ Data quality
+ Skills availability
+ Backup and recovery
+ Locations and placement
+ Privacy and sensitive data
+ Disaster recovery
+ Schema on read vs schema on write
    * Bringing the analytical capabilities to the data, VS
    * Bringing the data to the analytical capabilities through staging, extracting, transforming and loading

## Enterprise Big Data Architectural Components
- Governance
    + Govern data quality
- Operations, Infrastructure, and DevOps
- Monitoring
- Security and privacy
    + Authentication
    + Authorization
    + Accounting
    + Data protection
    + Compliance
- Data Aquisition, Ingestion, and Integration 
    + Messaging and message queues
    + ETL/ELT
    + Change data capture
    + FTP
    * API/ODBC
    * Replication
    * Bulk movement
    * Virtualization
    * Analytics types and options on ingestion - Oracle
        * Sensor-based real-time events
        * Near real-time transaction events
        * Real-time analytics
        * Near real time analytics
        * No immediate analytics
- Data Processing
    + Batch and stream processing/computing (velocity)
        * Massive scaling and processing of multiple concurrent input streams
    + Parallel computing platform
        * Clusters or grids
        * Massively parallel processing (MPP)
        * High performance computing (HPC)
    + Options - Oracle
        * Leave it at the point of capture
        * Add minor transformations
        * ETL data to analytical platform
        * Export data to desktops
    + Fast data - Oracle
        * Streams
        * Events
        * Actions
- Data Access
    + Querying
    + Real-time analytics
    + BI analytics
    + MapReduce analytics
- Data Modeling and Structure
    + Star schema
    + Snowflake schema
- Data Analysis, data mining, discovery, simulation, and optimization
    + Advanced analytics and modeling
    + Text and natural language analytics
    + Video and voice analytics
    + Geospatial analytics
    + Data visualization
    + Data mining
    + Where to do analysis - Oracle
        * At ingest – real time evaluation
        * In a raw data reservoir
        * In a discovery lab
        * In a data warehouse/mart
        * In BI reporting tools
        * In the public cloud
        * On premises
    + Data sets
    + Data science
    + Data discovery
    + In-place analytics
    + Faceted analytics
    + SQL analytics
- Data Storage and Management
    + Data lake
    * Data warehouse (volume), aka enterprise information store
        - Centralized, integrated data store
        - Powers BI analytics, reporting, and drives actionable insights
        - Responsible for integrating data
        - Structured, prepared, and stored data optimized for
            + Analytical applications and decision support
            + Querying and reporting
            + Data mining
        - In-database analytics
        - Operational analytics
        - MPP engine
        - 'Deep analytical appliance' - IBM
    * Operational data store (ODS)
    * Database Systems and DBMS
        - Relational (RDBMS)
        - NoSQL
            + Real-time analytics and insights
        - NewSQL
        - Hybrid
    * Data marts
        - Data warehouse extracted data subsets oriented to speciﬁc business lines, departments or analytical applications
    * File systems (Non-distributed)
    * Distributed file systems (e.g., HDFS) and Hadoop (volume and variety)
        - Real-time and MapReduce analytics and insights
        - Deep analysis of petabytes of structured and unstructured data
    * In-memory
    * Data factory
    * Data Reservoir
    * Dedicated and ad-hoc
        - Discovery labs
        - Sandboxes
- Data lifecycle management
    + Rule-based Data and Policy Tracking
    + Data compression
    + Data archiving
- Deployment Choice
    + On-premise, aka traditional IT
    + In-cloud
        * Public cloud
        * Private cloud
    + Appliance
    + Managed services
- Presentation, Analytics, and Applications (visibility)
    + Browser/web
    + Mobile
    + Desktop
    + Dashboards
    + Reports
    + Notifications and messaging
    + Scorecards
    + Charts and graphics
    + Visualization and discovery
    + Search
    + Alerting
    + EPM and BI applications
    + Recommendations

## Enterprise Big Data Components
- http://hortonworks.com/wp-content/uploads/2014/03/11.png

## Big Data Processing Key Functional Capabilities - IBM
- Data ingestion
    + Optimize the process of loading data in the data store to support time-sensitive analytic goals.
- Search and survey
    + Secure federated navigation and discovery across all enterprise content.
- Data transformation
    + Convert data values from source system and format to destination system and format.
- Analytics
    + Discover and communicate meaningful patterns in data.
- Actionable decisions
    + Make repeatable, real-time decisions about organizational policies and business rules.
- Discover and explore
    + Discover, navigate, and visualize vast amounts of structured and unstructured information across many enterprise systems and data repositories.
- Reporting, dashboards, and visualizations
    + Provide reports, analysis, dashboards, and scorecards to help support the way that people think and work.
- Provisioning
    + Deploy and orchestrate on-premises and off-premises components of a big data ecosystem.
- Monitoring and service management
    + Conduct end-to-end monitoring of services in the data center and the underlying infrastructure.
- Security and trust
    + Detect, prevent, and otherwise address system breaches in the big data ecosystem.
- Collaborate and share

## Big data and analytics architecture on cloud - IBM
- Analytics-as-a-service
    + Consumes both data at rest and in motion
    + Applies analytical algorithms
    + Provides
        * Dashboards
        * Reports
        * Visualizations
        * Insights
        * Predictive modeling
    + Abstracts away all complexity of data collection, storage, and cleansing
- Data-as-a-service
    + Data-at-rest-service
    + Data-in-motion-service
- NoSQL tools (Hive, Pig, BigSQL, ...)
- EMR clusters (Hadoop, Cassandra, MongoDB, ...) and Traditional DW
- Big data file system (HDFS, CFS, GPFS, S3, ...)
- Infrastructure & Appliances (Baremetal or IaaS) and object storage

## The Oracle Enterprise Architecture Development Process (OADP)
- Designed to be a flexible and a “just-in-time” architecture development approach
- Key Steps
    + Establish Business Context and Scope
    + Establish an Architecture Vision
    + Assess the Current State
    + Establish Future State and Economic Model
    + Develop a Strategic Roadmap
    + Establish Governance over the Architecture

## Data Storage Functions
- Staging
    + Temporary storage
    + Used for cleaning, integration and transformation routines
- Data management
    + Long-time managed storage
    + Clean and integrated data
- Sandboxing
    + Temporary data stores
    + Used by people, groups, and departments
    + Experimentation with data, processing, and analysis techniques
- Application optimized storage
    + Example usage = data mart
- Archive and raw data archive
    + Raw, processed, and transformed data

## [The 7 V's of Big Data](https://www.impactradius.com/blog/7-vs-big-data/)
+ Volume - Scale of data
+ Variety - Different forms of data
+ Velocity - Analysis of streaming data
+ Veracity - Overall quality and correctness of the data
    * Garbage in, garbage out
    * Assess the truthfulness and accuracy of the data as well as identify missing or incomplete information
- Visibility/Visualization
- Value
- Variability

## Data types and sources
+ Structured
    * Transactions
    * Master and reference
+ Unstructured
    * Text
    * Image
    * Video
    * Audio
    * Social
+ Semi-structured
    * Machine generated
+ Data storage (databases)
+ Sensors
+ Events
+ [Parquet](https://parquet.apache.org/)
+ RFID tags
+ Instore WiFi logs
+ Machine Logs
    * Application
    * Events
    * Server
    * CDRs
    * Clickstream
+ Text, including documents, emails, scanned documents, records, ...
+ Social networks
+ Public web
+ Geo-location/geospatial
+ Feeds
+ Machine generated
+ Clickstream
+ Software
+ Media
    * Images
    * Video
    * Audio
+ Business applications
    * OLTP - Online transaction processing
    * ERP - Enterprise resource planning
    * CRM - Customer relationship management
    * SCM - Supply chain management
    * HR
    * Product/Project management
+ Online chat
+ Merchant listings
+ DMP - Data management platform (advertising/marketing)
+ CDR - Call detail records
+ Surveys, questionnaires, binary questions, and sentiment
+ Billing data
+ Product catalog
+ Network data
+ Subscriber data
+ Staffing
+ Inventory
+ POS and transactional
+ eCommerce transactions
+ Biometrics
+ Mobile devices
+ Weather data
+ Traffic pattern data
+ Mobile devices
+ Surveillance

## Database Considerations and Tradeoffs
- ACID
    + Atomicity - An atomic transaction is an indivisible and irreducible series of database operations such that either all occur, or nothing occurs
    + Consistency - The requirement that any given database transaction must change affected data only in allowed ways, and that any data written to the database must be valid according to all defined rules, including constraints, cascades, triggers, and any combination thereof
    + Isolation - How transaction integrity is visible to other users and systems, i.e., how/when the changes made by one operation become visible to other
    + Durability - Guarantees that transactions that have committed will survive permanently
- BASE
    + Basically Available - Any data request should receive a response, but that response may indicate a failure or changing state as opposed to the requested data
    + Soft state - Given eventual consistency, the system may be in a changing state until consistency is reached
    + Eventual consistency - Informally guarantees that (to achieve high availability), if no new updates are made to a given data item, eventually all accesses to that item will return the last updated value
- CAP (Brewers theorem) and PACELC
    + Consistency - All clients always have the same view of the data
    + Availability - Each client can always read and write
    + Partition tolerance - The system works well despite physical network partitions
- Consistency vs eventually consistency
- Speed and performance
- Locks
    + Lock contention
    + Long term blocking
    + Database deadlocks
    + System deadlocks
- Schema on write vs schema on read
- Isolation levels
- Concurrency control
- Different read types (e.g., dirty, non-repeatable, phantom, ...)

## Databases by CAP (non-exhaustive)
- CA - Typically deal with P with replication
    + RDBMS
- AP - Achieve "eventual consistency" through replication and verification
    + Dynamo
    + Voldemort
    + Cassandra
    + SimpleDB
    + CouchDB
    + Riak
- CP - Have trouble with availability while keeping data consistent across partitioned nodes
    + BigTable
    + MongoDB
    + HBase
    + MemcacheDB
    + Redis

**Big Data Architecture Patterns**
- [Polyglot](http://datadventures.ghost.io/2014/07/06/polyglot-processing/)
- [Lambda](http://lambda-architecture.net/)
- [Kappa](http://milinda.pathirage.org/kappa-architecture.com/)
- [IOT-A](http://iot-a.info/)
    + Message Queue/Stream Processing (MQ/SP) block
        * Buffer data
            - Processing speed
            - Throughput handling of downstream components
            - Micro-batching can increase ingestion rate into downstream components
        * Process and filter data
            - Cleaning and removal
            - Stream processing
                + Continuous queries
                + Aggregates
                + Counts
                + Real-time machine learning/AI
        * Output
            - Real-time
            - Ingest data into downstream blocks (DB and/or DFS)
        * Example technologies
            - [Kafka](http://kafka.apache.org/)
            - [Spark](http://spark.apache.org/)
            - [Fluentd](http://www.fluentd.org/)
            - [Storm](http://storm.apache.org/)
    + Database (DB) block
        * Provides granular, structured, low-latency access to the data
        * Typically NoSQL
            - MongoDB
            - Cassandra
            - HBase
        * Output
            - Interactive ad-hoc querying
                + Data store API (e.g., HBase, MongoDB, ...)
                + Standard SQL interface
        * Example technologies
            - [Spark](http://spark.apache.org/)
            - [Drill](http://incubator.apache.org/drill/)
    + Distributed File System (DFS) block
        * Batch jobs over entire dataset
            - Aggregations
            - Reporting
            - Integration across data sources
                - E.g., with unstructured data
        * Long term storage (archiving)
        * Example technologies
            - [Hive](http://hive.apache.org/)
            - [Mahout](http://mahout.apache.org/)

## IoT Solution Components
- Connected devices
- Native and processed raw data support
    + Input data typically time-series
- Support for a variety of workload types
    + Stream processing
    + Low-latency data queries
    + SLAs (depends on application)
        * [Recovery Point Objective](https://en.wikipedia.org/wiki/Recovery_point_objective)
        * [Recovery Time Objective](https://en.wikipedia.org/wiki/Recovery_time_objective)
        * Availability
        * Latency
        * Disaster recovery
    + Security
    + Privacy
        * ACLs
        * Data encryption and masking
- Processing and output
    + Real-time stream
    + Interactive querying
    + Output generated in batches
    + Data transformations
    + Aggregations and computation
    + Data integration and enrichment
- Data movement and storage
    + One or more data stores
- Leverage _big data_ approach
    + Scale out techniques and storage on commodity hardware
        * Historical data/references (_volume_)
    + Schema-on-read (e.g., data lake)
    + Community defined interfaces
    + Many different data formats and non-relational sensor data (_variety_)
    + High rate data generation and handling via data streams in IoT context (_velocity_)
- Analytics
- APIs/SDKs
- Applications and presentation

**Big Data and IoT Tech Stacks**
- SACK
    + Spark - Digest
    + Akka - Ingest
    + Cassandra
    + Kafka
- SMACK
    + Spark
    + Mesos
    + Akka
    + Cassandra
    + Kafka

## Hadoop Benefits
- Built on the _shared nothing_ principle
    + Each node is independent and self-sufficient
- Ability to store any and all data types relatively cheap
- Ability to process any and all data quickly and relatively cheap
- Vast community, ecosystem, and pluggable architecture
- Scalable, flexible, computational model

## Data Lake vs Data Warehouse
- Data Warehouse (EDW)
    + [Definition](https://en.wikipedia.org/wiki/Data_warehouse) - A system used for reporting and data analysis, and is considered a core component of business intelligence
    + Characteristics
        * Data
            - Structured
            - Processed
        * Schema-on-write processing
        * Relatively expensive for large volumes
        * Fixed configuration and less flexible
        * Better suited for business intelligence and business professionals
    + Considerations
    + Technologies
        * AWS Redshift
- Data Lake
    + [Definition](http://www.kdnuggets.com/2015/09/data-lake-vs-data-warehouse-key-differences.html) - A data lake is a storage repository that holds a vast amount of raw data in its native format, including structured, semi-structured, and unstructured data. The data structure and requirements are not defined until the data is needed.
    + Characteristics
        * Data
            - Structured, semi-structured, unstructured
            - Raw
        * A data lake delivers maximum scale and insight with the lowest possible friction and cost
        * Increased efficiency
        * Reduced storage costs
        * Data processing workload optimization, including data integration and transformation
        * Schema-on-read processing and associated flexibility and new opportunities
        * Multi-use and multi-workload data processing on same data from batch to real-time across business units
        * Eliminate need for ETL and associated costs
        * Keep 100% of source data and historical data for ongoing exploration (both raw and processed)   
        * Easy and dynamic configuration and reconfiguration
        * Better suited for data scientists
    + Considerations
    + Technologies
        * Hadoop
        * Apache YARN

## Data Processing and access methods/patterns compared
- Batch
    + Process batches of data on regular time intervals, e.g., hourly, daily, overnight, etc.
    + Aka, MapReduce
- Real-time
    + Monitor and react in real time
    + Key-value data stores, such as NoSQL, allow for high performance, index-based retrieval - Oracle
- Streaming
- Interactive
    + Data analysts reviewing data
- Online
- Search
- In-memory

## Offline vs Online Learning

Coming soon...

## Big Data Best Practices - Oracle
- Align Big Data with Specific Business Goals
- Ease Skills Shortage with Standards and Governance
- Optimize Knowledge Transfer with a Center of Excellence
- Top Payoff is Aligning Unstructured with Structured Data
- Plan Your Discovery Lab for Performance
- Align with the Cloud Operating Model

## Architecture Principles - Oracle
- Accommodate All Forms of Data
- Consistent Information and Object Model
- Integrated Analysis
- Insight to Action

## IBM Data Governance Council Maturity Model
- Organizational Structures & Awareness
- Stewardship
- Policy
- Value Creation
- Data Risk Management & Compliance
- Information Security & Privacy
- Data Architecture
- Data Quality Management
- Classification & Metadata
- Information Lifecycle Management
- Audit Information, Logging & Reporting