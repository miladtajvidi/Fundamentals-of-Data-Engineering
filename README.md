<p align="center">
  <img src="./Oreilly_DE.png" alt="Description of image" width="500" height="600">
</p>

# Fundamentals-of-Data-Engineering

This repo contains the still-available additional reading resources and a glossary of data engineering terms and concepts cited in the [Fundamentals of Data Engineering: Plan and Build Robust Data Systems](https://www.amazon.ca/Fundamentals-Data-Engineering-Robust-Systems/dp/1098108302) by Joe Reis & Matt Housley.<br>
**The purpose of this repo is to serve as a complimentary resource for ease of access when you're reading the book.
Please contact me know if you're one of the authors and want your papers' links removed.<br>
Please note that the hyperlink titles only include titles to make your search convenient. Please remember to cite them properly in your works.<br>
Please give this repo a star if you found it helpful!**

# Glossary

## 1. Foundations of data engineering
- data engineering <br>
- data engineering lifecycle <br>
- data lifecycle <br>
- data architects <br>
- data engineers <br>
- data maturity <br>
- Data Management Maturity (DMM) <br>
- Data Science Hierarchy of Needs <br>
- big data era <br>
- data lifecycle engineers <br>
- stakeholders <br>
- upstream stakeholders <br>
- downstream stakeholders <br>
- business stakeholders <br>
- systems stakeholder <br>

## 2. Data architecture and system design
- data architecture <br>
- enterprise architecture <br>
- business architecture <br>
- technical architecture <br>
- operational architecture <br>
- application architecture <br>
- architecture tiers <br>
- baseline architecture <br>
- target architecture <br>
- agile architecture <br>
- collaborative architecture <br>
- command-and-control architecture <br>
- event-driven architecture <br>
- microservices architecture <br>
- monolithic architectures <br>
- distributed monolith pattern <br>
- n-tier architectures <br>
- single-tier architectures <br>
- three-tier architectures <br>
- multitier architectures <br>
- shared-nothing architectures <br>
- shared disk architectures <br>
- domains <br>
- services <br>
- tight coupling <br>
- loose coupling <br>
- decoupling <br>
- modularization <br>
- scalability <br>
- failure planning <br>
- resilience <br>
- elasticity <br>
- availability <br>
- reliability <br>

## 3. Data engineering lifecycle stages
- generation stage <br>
- ingestion stage <br>
- storage stage <br>
- transformation stage <br>
- serving data stage <br>

## 4. Source systems and data generation
- source systems <br>
- application databases <br>
- transactional databases <br>
- OLTP systems <br>
- OLAP systems <br>
- APIs <br>
- REST APIs <br>
- GraphQL <br>
- gRPC <br>
- files <br>
- file formats <br>
- logs <br>
- database logs <br>
- real-time logs <br>
- event-based data <br>
- messages <br>
- streams <br>
- IoT <br>
- devices <br>
- third-party data sources <br>
- data marketplaces <br>
- data sharing <br>
- analog data <br>
- digital data <br>
- structured data <br>
- semistructured data <br>
- unstructured data <br>
- bounded data <br>
- unbounded data <br>
- event time <br>
- ingestion time <br>
- process time <br>
- processing time <br>
- types of time <br>

## 5. Ingestion and data movement
- data ingestion <br>
- batch data ingestion <br>
- streaming data ingestion <br>
- near real-time ingestion <br>
- real-time ingestion <br>
- synchronous ingestion <br>
- asynchronous ingestion <br>
- push model <br>
- pull model <br>
- payloads <br>
- throughput <br>
- durability <br>
- frequency <br>
- size <br>
- shape <br>
- location <br>
- change data capture (CDC) <br>
- continuous CDC <br>
- batch-oriented CDC <br>
- log-based CDC <br>
- fast-follower CDC <br>
- database replication <br>
- direct database connection <br>
- file export <br>
- file-based export <br>
- managed data connectors <br>
- shell interface <br>
- web interfaces <br>
- web scraping <br>
- webhooks <br>
- SFTP <br>
- SCP <br>
- SSH protocol <br>
- electronic data interchange (EDI) <br>
- transfer appliances <br>
- data migration <br>
- dead-letter queues <br>
- error handling <br>
- snapshots <br>
- incremental updates <br>
- full snapshots <br>
- update operations <br>

## 6. Messaging, events, and streaming systems
- event-streaming platforms <br>
- message queues <br>
- consumers <br>
- publishers <br>
- FIFO <br>
- partition keys <br>
- stream partitions <br>
- topics <br>
- state <br>
- timestamps <br>
- idempotent message systems <br>
- hotspotting <br>
- late-arriving data <br>
- replay <br>
- maximum message retention time <br>
- streaming buffers <br>
- Kappa architecture <br>
- Lambda architecture <br>
- Dataflow model <br>
- stream-to-batch storage architecture <br>

## 7. Storage systems and storage architecture
- data storage systems <br>
- storage abstractions <br>
- storage lifecycle <br>
- block storage <br>
- file storage <br>
- object storage <br>
- streaming storage <br>
- distributed storage <br>
- single machine storage <br>
- cache and memory-based storage <br>
- memory-based storage systems <br>
- object store-backed filesystems <br>
- HDFS <br>
- NAS <br>
- SAN <br>
- local disk storage <br>
- instance store volumes <br>
- EBS <br>
- archival storage <br>
- cold storage <br>
- hot storage <br>
- storage classes <br>
- storage tiers <br>
- single-tenant storage <br>
- multitenant storage <br>
- data retention <br>
- time to live (TTL) <br>
- automated lifecycle policies <br>
- automatic data lifecycle management <br>
- separation of compute from storage <br>
- hybrid object storage <br>
- hybrid separation <br>
- data catalogs <br>
- schema on read <br>
- schema on write <br>

## 8. Physical infrastructure and hardware concepts
- magnetic disks <br>
- solid-state drives (SSDs) <br>
- RAM <br>
- DRAM <br>
- NVRAM <br>
- areal density <br>
- linear density <br>
- disk transfer speed <br>
- rotational latency <br>
- cache hierarchy <br>
- reverse cache <br>
- CPU <br>
- networking <br>
- serialization <br>
- decompression <br>
- compression algorithms <br>
- lossless compression <br>
- lossy compression <br>
- Harvard architecture <br>
- von Neumann architecture <br>

## 9. Data formats, serialization, and table/storage formats
- CSV <br>
- JSON <br>
- JSONL <br>
- XML <br>
- Avro <br>
- Apache Arrow <br>
- Parquet <br>
- ORC <br>
- row-based serialization <br>
- columnar serialization <br>
- hybrid serialization <br>
- in-memory serialization <br>
- serialization formats <br>
- database storage engines <br>
- Iceberg <br>
- Hudi <br>
- table management technologies <br>

## 10. Databases and data stores
- relational databases <br>
- RDBMSs <br>
- DBMSs <br>
- nonrelational / NoSQL databases <br>
- document stores <br>
- key-value databases <br>
- graph databases <br>
- wide-column databases <br>
- time-series databases <br>
- search databases <br>
- massively parallel processing (MPP) databases <br>
- real-time analytical databases <br>
- query optimizers <br>
- indexes <br>
- B-trees <br>
- log-structured merge-trees (LSMs) <br>
- collections <br>
- tables <br>
- documents <br>
- relations <br>
- rows <br>
- columns <br>
- fields <br>
- primary keys <br>
- foreign keys <br>

## 11. Querying and SQL
- queries <br>
- query engines <br>
- query execution <br>
- SQL <br>
- DDL <br>
- DML <br>
- DCL <br>
- TCL <br>
- CTEs <br>
- nested subqueries <br>
- temporary tables <br>
- explain plan <br>
- full table scans <br>
- query performance <br>
- query pushdown <br>
- federated queries <br>
- prejoining data <br>
- row explosion <br>
- pruning <br>
- vacuuming <br>
- concurrency <br>
- latency <br>

## 12. Transformation and processing
- transformations <br>
- batch transformations <br>
- streaming transformations <br>
- ETL <br>
- ELT <br>
- STL <br>
- extract <br>
- load <br>
- transform-on-read ELT <br>
- reverse ETL <br>
- data wrangling <br>
- derived data <br>
- business logic <br>
- composable materialized views <br>
- materialized views <br>
- views <br>
- live tables <br>
- Spark API <br>
- Spark <br>
- Apache Beam <br>
- MapReduce <br>
- memory caching <br>
- spill to disk <br>
- shuffle hash joins <br>
- broadcast joins <br>
- distributed joins <br>
- node joins <br>
- micro-batch approach <br>
- data virtualization <br>

## 13. Data modeling and schema design
- data modeling <br>
- conceptual data models <br>
- logical data models <br>
- physical data models <br>
- normalization <br>
- denormalization <br>
- normal forms <br>
- 1NF <br>
- 2NF <br>
- 3NF <br>
- Boyce-Codd <br>
- partial dependency <br>
- transitive dependency <br>
- grain <br>
- star schema <br>
- fact tables <br>
- dimension tables <br>
- conformed dimension <br>
- slowly changing dimensions (SCDs) <br>
- wide denormalized tables <br>
- PIT tables <br>
- bridge tables <br>
- normalized schemas <br>
- relational schema <br>
- Data Vault <br>
- hubs <br>
- links <br>
- satellites <br>
- Inmon <br>
- Kimball <br>
- schema evolution <br>
- schema updates <br>
- schema changes <br>
- schema registries <br>
- fixed schema <br>
- schemaless option <br>

## 14. Analytics, BI, and serving data to users
- serving data <br>
- business intelligence (BI) <br>
- dashboards <br>
- reports <br>
- ad hoc analysis <br>
- business analytics <br>
- operational analytics <br>
- embedded analytics <br>
- analytics as code <br>
- headless BI <br>
- semantic layers <br>
- metrics layers <br>
- notebooks <br>
- file exchange <br>
- serving data via databases <br>
- self-service data <br>
- data products <br>
- data definitions <br>
- implicit data definitions <br>
- institutional knowledge <br>
- trust <br>
- use cases <br>
- validation <br>

## 15. Machine learning and data products
- machine learning <br>
- ML <br>
- machine learning engineers <br>
- MLOps <br>
- featurization <br>
- data featurization <br>
- AI researchers <br>
- data scientists <br>
- data applications <br>
- fusion of data with applications <br>
- tight feedback between applications and machine learning <br>

## 16. Governance, metadata, quality, and management
- data management <br>
- data governance <br>
- data accountability <br>
- data quality <br>
- quality <br>
- accuracy <br>
- completeness <br>
- timeliness <br>
- discoverability <br>
- metadata <br>
- business metadata <br>
- technical metadata <br>
- operational metadata <br>
- pipeline metadata <br>
- schema metadata <br>
- reference metadata <br>
- data-lineage metadata <br>
- version metadata <br>
- autogenerated metadata <br>
- human-generated metadata <br>
- data lineage <br>
- data lineage tools <br>
- data observability <br>
- DODD <br>
- data contracts <br>
- master data management <br>
- golden records <br>
- lookup data <br>
- data integration <br>
- lifecycle management <br>
- compliance <br>
- regulations <br>

## 17. DataOps, orchestration, and software engineering practices
- DataOps <br>
- data orchestration <br>
- orchestration <br>
- DAGs <br>
- schedulers <br>
- Airflow <br>
- Airflow DAG <br>
- pipelines as code <br>
- infrastructure as code (IaC) <br>
- automation <br>
- monitoring <br>
- observability <br>
- incident response <br>
- TDD <br>
- software engineering <br>
- open source frameworks <br>
- core data processing code <br>
- streaming data processing <br>
- windowing methods <br>
- data reliability engineers <br>
- touchless production <br>

## 18. Security, privacy, and compliance
- security <br>
- privacy <br>
- data ethics and privacy <br>
- active security <br>
- defensive posture <br>
- paranoia <br>
- negative thinking <br>
- access policies <br>
- principle of least privilege <br>
- zero-trust security models <br>
- shared responsibility model <br>
- network security <br>
- encryption <br>
- full-disk encryption <br>
- logging <br>
- alerting <br>
- backups <br>
- disaster prevention <br>
- security policies <br>
- patches <br>
- credential handling <br>
- public access <br>
- permissions monitoring <br>
- resource use monitoring <br>
- human security breaches <br>
- internal security research <br>
- FERPA <br>
- HIPAA <br>
- compliance <br>
- regulations <br>

## 19. Cloud, infrastructure choices, and platform strategy
- cloud services <br>
- cloud data warehouses <br>
- cloud networking <br>
- content delivery networks <br>
- multicloud <br>
- hybrid cloud <br>
- cloud repatriation <br>
- cloud of clouds <br>
- direct network connections <br>
- availability zones <br>
- regions <br>
- multiregion networking <br>
- IaaS <br>
- PaaS <br>
- SaaS <br>
- serverless <br>
- servers <br>
- container platforms <br>
- lightweight virtual machines <br>
- cloud economics <br>
- FinOps <br>
- cost optimization <br>
- TCO <br>
- TOCO <br>
- capex <br>
- opex <br>
- data gravity <br>
- data egress costs <br>
- pay-as-you-go systems <br>
- cloud-first approach <br>
- proprietary cloud offerings <br>

## 20. Technology selection and platform strategy
- build versus buy <br>
- open source software <br>
- commercial open source software <br>
- community-managed open source software <br>
- proprietary walled gardens <br>
- interoperability <br>
- speed to market <br>
- immutable versus transitory technologies <br>
- monolith versus modular <br>
- serverless versus servers <br>
- benchmarks <br>
- location <br>
- one-size-fits-all solutions <br>
- shiny object syndrome <br>
- resume-driven development <br>
- cargo-cult engineering <br>
- overarchitecting <br>
- curse of familiarity <br>
- reversible decisions <br>
- one-way doors <br>
- two-way doors <br>
- choose common components wisely <br>

## 21. Modern platform trends and emerging patterns
- modern data stack <br>
- live data stacks <br>
- data platforms <br>
- cloud-scale data OS <br>
- data connectors <br>
- off-the-shelf data connectors <br>
- improved interoperability <br>
- move toward live data stacks <br>
- real-time analytical databases <br>
- streaming pipelines <br>
- rise of spreadsheets <br>
- fusion of data with applications <br>
- lakehouses <br>
- data lakehouses <br>
- trend toward convergence <br>



# Additional Reading

## Chapter 1: Data Engineering Described

- [The AI Hierarchy of Needs](https://hackernoon.com/the-ai-hierarchy-of-needs-18f111fcc007) <br>
- [The AlphaGo research web page](https://deepmind.google/research/alphago/) <br>
- [Building Analytics Teams](https://www.amazon.ca/Building-Analytics-Teams-intelligence-improvement/dp/1800203160) <br>
- [What is Data Engineering?](https://www.oreilly.com/library/view/what-is-data/9781492075578/ch01.html) <br>
- [Data as a Product vs. Data as a Service](https://readtechnically.medium.com/data-as-a-product-vs-data-as-a-service-d9f7e622dc55) <br>
- [Data engineering: A quick and simple definition](https://www.oreilly.com/content/data-engineering-a-quick-and-simple-definition/) <br>
- [Data Teams](https://www.amazon.ca/Data-Teams-Management-Successful-Data-Focused/dp/1484262271) <br>
- [Doing Data Science at Twitter](https://medium.com/@rchang/my-two-year-journey-as-a-data-scientist-at-twitter-f0c13298aee6) <br>
- [The Downfall of the Data Engineer](https://maximebeauchemin.medium.com/the-downfall-of-the-data-engineer-5bfb701e5d6b) <br>
- [The Future of Data Engineering is the Convergence of Disciplines](https://mode.com/blog/future-of-data-engineering-jasmine-tsai) <br>
- [How CEOs Can Lead a Data-Driven Culture](https://hbr.org/2020/03/how-ceos-can-lead-a-data-driven-culture) <br>
- [Information Management Body of Knowledge Wikipedia page](https://en.wikipedia.org/wiki/Information_Management_Body_of_Knowledge) <br>
- [Information management Wikipedia page](https://en.wikipedia.org/wiki/Information_management) <br>
- [On Complexity in Big Data](https://www.oreilly.com/radar/on-complexity-in-big-data/) <br>
- [OpenAI’s new language generator GPT-3 is shockingly good—and completely mindless](https://www.technologyreview.com/2020/07/20/1005454/openai-machine-learning-language-generator-gpt-3-nlp/) <br>
- [The Rise of the Data Engineer](https://www.freecodecamp.org/news/the-rise-of-the-data-engineer-91be18f1e603/) <br>
- [A Short History Of Big Data](https://datafloq.com/big-data-history/) <br>
- [Skills of the Data Architect](https://robertlambert.net/2012/11/skills-of-the-data-architect/) <br>
- [The 3 Levels of Data Analysis- A Framework for Assessing Data Organization Maturity](https://about.gitlab.com/blog/three-levels-data-analysis/) <br>
- [Data architect role](https://www.cio.com/article/190852/what-is-a-data-architect-its-data-framework-visionary.html) <br>
- [Which profession is more complex to become, a data engineer or a data scientist?](https://www.quora.com/Which-profession-is-more-complex-to-become-a-data-engineer-or-a-data-scientist) <br>




## Chapter 2: The Data Engineering Lifecycle

- [A comparison of data processing frameworks](https://kapernikov.com/a-comparison-of-data-processing-frameworks/) <br>
- [DAMA website](https://dama.org/learning-resources/dama-data-management-body-of-knowledge-dmbok/) <br>
- [The Dataflow Model: A Practical Approach to Balancing Correctness, Latency, and Cost in Massive-Scale, Unbounded, Out-of-Order Data Processing](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43864.pdf) <br>
- [Data processing Wikipedia page](https://en.wikipedia.org/wiki/Data_processing) <br>
- [Data transformation Wikipedia page](https://en.wikipedia.org/wiki/Data_transformation_(computing)) <br>
- [Democratizing Data at Airbnb](https://medium.com/airbnb-engineering/democratizing-data-at-airbnb-852d76c51770) <br>
- [5 steps to begin collecting the value of your data](https://www.lean-data.nl/tag/operational-metadata/) <br>
- [Getting started with DevOps automation](https://github.blog/enterprise-software/devops/getting-started-with-devops-automation/) <br>
- [Incident management in the age of DevOps](https://www.atlassian.com/incident-management/devops) <br>
- [An Introduction to Dagster: The orchestrator for the full data lifecycle](https://www.youtube.com/watch?v=MF5OaQEOF2E) <br>
- [Is DevOps Related to DataOps?](https://www.dataops.dev/dataops-vs-devops) <br>
- [What is incident response?](https://www.atlassian.com/incident-management/incident-response) <br>
- [To How To Stay Ahead of Data Debt and Downtime](https://www.secoda.co/blog/staying-ahead-of-data-debt) <br>
- [What Is Metadata?](https://www.dataversity.net/data-concepts/what-is-metadata/) <br>

## Chapter 3: Designing Good Data Architecture

- [Anemic Domain Model](https://martinfowler.com/bliki/AnemicDomainModel.html) <br>
- [Big data architectures](https://learn.microsoft.com/en-us/azure/architecture/databases/guide/big-data-architectures) <br>
- [Bounded Context](https://martinfowler.com/bliki/BoundedContext.html) <br>
- [The Building Blocks of a Modern Data Platform](https://towardsdatascience.com/the-building-blocks-of-a-modern-data-platform-92e46061165/) <br>
- [Choosing Open Wisely](https://www.snowflake.com/en/blog/choosing-open-wisely/) <br>
- [Choosing the Right Architecture for Global Data Distribution](https://docs.cloud.google.com/architecture/hybrid-multicloud-patterns) <br>
- [Data Orientation Wikipedia page](https://en.wikipedia.org/wiki/Data_orientation) <br>
- [A comparison of data processing frameworks](https://kapernikov.com/a-comparison-of-data-processing-frameworks/) <br>
- [The Cost of Cloud, a Trillion Dollar Paradox](https://a16z.com/the-cost-of-cloud-a-trillion-dollar-paradox/) <br>
- [The curse of the data lake monster](https://www.thoughtworks.com/insights/blog/curse-data-lake-monster) <br>
- [Data Architecture: A Primer for the Data Scientist](https://www.oreilly.com/library/view/data-architecture-a/9780128169179/) <br>
- [Data Architecture: Complex vs. Complicated](https://datalere.com/articles/data-architecture-complex-vs-complicated) <br>
- [Data as a Product vs. Data as a Service](https://readtechnically.medium.com/data-as-a-product-vs-data-as-a-service-d9f7e622dc55) <br>
- [The Data Dichotomy: Rethinking the Way We Treat Data and Services](https://www.confluent.io/blog/data-dichotomy-rethinking-the-way-we-treat-data-and-services/) <br>
- [Data Fabric defined](https://www.jamesserra.com/archive/2021/06/data-fabric-defined/) <br>
- [Data Warehouse Architecture: Overview](https://roelantvos.com/blog/enterprise_bi_architecture_overview/documentation-breakdown/) <br>
- [Disasters I've seen in a microservices world](https://world.hey.com/joaoqalves/disasters-i-ve-seen-in-a-microservices-world-a9137a51) <br>
- [Domain Driven Design](https://martinfowler.com/bliki/DomainDrivenDesign.html) <br>
- [Down with pipeline debt: introducing Great Expectations](https://medium.com/@expectgreatdata/down-with-pipeline-debt-introducing-great-expectations-862ddc46782a) <br>
- [Eager Read Derivation](https://martinfowler.com/bliki/EagerReadDerivation.html) <br>
- [End-To-End Serverless ETL Orchestration in AWS: A Guide](https://aws.plainenglish.io/end-to-end-serverless-etl-orchestration-in-aws-322fedd4402f) <br>
- [The Role of Head of Enterprise Architecture in Driving Digital Transformation](https://www.gartner.com/en/information-technology/role/enterprise-architecture-technology-leaders) <br>
- [Event Sourcing](https://martinfowler.com/eaaDev/EventSourcing.html) <br>
- [Falling Back in Love with Data Pipelines](https://devops.com/falling-back-in-love-with-data-pipelines/) <br>
- [5 principles for cloud-native architecture—what it is and how to master it](https://cloud.google.com/blog/products/application-development/5-principles-for-cloud-native-architecture-what-it-is-and-how-to-master-it) <br>
- [Focusing on Events](https://martinfowler.com/eaaDev/EventNarrative.html) <br>
- [Functional Data Engineering — a modern paradigm for batch data processing](https://maximebeauchemin.medium.com/functional-data-engineering-a-modern-paradigm-for-batch-data-processing-2327ec32c42a) <br>
- [Google Cloud Well-Architected Framework](https://docs.cloud.google.com/architecture/framework) <br>
- [How to build a data architecture to drive innovation—today and tomorrow](https://www.mckinsey.com/capabilities/tech-and-ai/our-insights/how-to-build-a-data-architecture-to-drive-innovation-today-and-tomorrow) <br>
- [Introducing Dagster](https://medium.com/dagster-io/introducing-dagster-dbd28442b2b7) <br>
- [The Log: What every software engineer should know about real-time data's unifying abstraction](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying) <br>
- [Azure Architecture Center](https://learn.microsoft.com/en-us/azure/architecture/) <br>
- [Modern CI is Too Complex and Misdirected](https://gregoryszorc.com/blog/2021/04/07/modern-ci-is-too-complex-and-misdirected/) <br>
- [The Modern Data Stack: Past, Present, and Future](https://www.getdbt.com/blog/future-of-the-modern-data-stack) <br>
- [A personal implementation of Modern Data Architecture: Getting Strava data into Google Cloud Platform](https://medium.com/@reevery/a-personal-implementation-of-modern-data-architecture-getting-strava-data-into-google-cloud-49506446ebd4) <br>
- [Polyglot Persistence](https://martinfowler.com/bliki/PolyglotPersistence.html) <br>
- [Potemkin Data Science](https://mcorrell.medium.com/potemkin-data-science-fba2b5ba5cc6) <br>
- [Principled Data Engineering, Part I: Architectural Overview](https://medium.com/ssense-tech/principled-data-engineering-part-i-architectural-overview-6d4bdf89b657) <br>
- [Questioning the Lambda Architecture](https://www.oreilly.com/radar/questioning-the-lambda-architecture/) <br>
- [Reliable Microservices Data Exchange With the Outbox Pattern](https://debezium.io/blog/2019/02/19/reliable-microservices-data-exchange-with-the-outbox-pattern/) <br>
- [Reporting Database](https://martinfowler.com/bliki/ReportingDatabase.html) <br>
- [The Rise of the Metadata Lake](https://towardsdatascience.com/the-rise-of-the-metadata-lake-1e95127594de/) <br>
- [Run Your Data Team Like A Product Team](https://locallyoptimistic.com/post/run-your-data-team-like-a-product-team/) <br>
- [7 Modern Data Architecture Principles](https://www.atscale.com/blog/the-six-modern-principles-of-modern-data-architecture/) <br>
- [Data Warehouse Architecture and Design: Best Practices](https://www.snowflake.com/en/fundamentals/data-warehouse-architecture-and-design/) <br>
- [Software infrastructure 2.0: a wishlist](https://erikbern.com/2021/04/19/software-infrastructure-2.0-a-wishlist.html) <br>
- [To How To Stay Ahead of Data Debt and Downtime](https://www.secoda.co/blog/staying-ahead-of-data-debt) <br>
- [Tactics vs. Strategy (SOA & The Tarpit of Irrelevancy)](https://memeagora.blogspot.com/2009/01/tactics-vs-strategy-soa-tarpit-of.html) <br>
- [Test data quality at scale with Deequ](https://aws.amazon.com/blogs/big-data/test-data-quality-at-scale-with-deequ/) <br>
- [What is three-tier architecture?](https://www.ibm.com/think/topics/three-tier-architecture?mhsrc=ibmsearch_a&mhq=three-tier%20architecture) <br>
- [The Top 5 Data Trends for CDOs to Watch Out for in 2021](https://towardsdatascience.com/the-top-5-data-trends-for-cdos-to-watch-out-for-in-2021-e230817bcb16/) <br>
- [240 tables and no documentation?](https://minimalmodeling.substack.com/p/240-tables-and-no-documentation) <br>
- [What is Data Observability? 5 Key Pillars To Know](https://www.montecarlodata.com/blog-what-is-data-observability/) <br>
- [Apache Flink Roadmap](https://flink.apache.org/what-is-flink/roadmap/) <br>
- [Utility Vs Strategic Dichotomy](https://martinfowler.com/bliki/UtilityVsStrategicDichotomy.html) <br>
- [What Is a Lakehouse?](https://www.databricks.com/blog/2020/01/30/what-is-a-data-lakehouse.html) <br>
- [What is data architecture? A framework to manage data](https://www.cio.com/article/190941/what-is-data-architecture-a-framework-for-managing-data.html) <br>
- [What is the Open Data Ecosystem and Why it’s Here To Stay](https://casberw.medium.com/what-is-the-open-data-ecosystem-and-why-its-here-to-stay-60c06f19011b) <br>
- [What’s wrong with MLOps?](https://laszlo.substack.com/p/whats-wrong-with-mlops) <br>
- [What the Heck is a Data Mesh?!](https://cnr.sh/posts/2021-06-08-what-the-heck-data-mesh/) <br>
- [Who Needs an Architect?](https://files.catwell.info/misc/mirror/2003-martin-fowler-who-needs-an-architect.pdf) <br>
- [Zachman Framework](https://en.wikipedia.org/wiki/Zachman_Framework) <br>


## Chapter 4: Choosing Technologies Across the Data Engineering Lifecycle

- [Cloud FinOps](https://www.oreilly.com/library/view/cloud-finops/9781492054610/) <br>
- [Cloud Infrastructure: The Definitive Guide for Beginners](https://www.lastweekinaws.com/blog/cloud-infrastructure-last-week-in-aws/) <br>
- [The Cost of Cloud, a Trillion Dollar Paradox](https://a16z.com/the-cost-of-cloud-a-trillion-dollar-paradox/) <br>
- [What is FinOps?](https://www.finops.org/introduction/what-is-finops/) <br>
- [Red Hot: The 2021 Machine Learning, AI and Data (MAD) Landscape](https://www.mattturck.com/data2021) <br>
- [What's Next for Analytical Databases? (MotherDuck)](https://www.youtube.com/watch?v=E2fi-Y6RiTw) <br>
- [The Unfulfilled Promise of Serverless](https://www.lastweekinaws.com/blog/the-unfulfilled-promise-of-serverless/) <br>
- [Understanding the modern data stack](https://www.fivetran.com/blog/what-is-the-modern-data-stack) <br>



## Chapter 5: Data Generation in Source Systems

- [Schema Evolution and Compatibility for Schema Registry on Confluent Platform](https://docs.confluent.io/platform/current/schema-registry/fundamentals/schema-evolution.html) <br>
- [Database Internals](https://www.oreilly.com/library/view/database-internals/9781492040330/) <br>
- [Database System Concepts](https://www.db-book.com/) <br>
- [Modernizing Business Data Indexing](https://engineeringblog.yelp.com/2021/06/modernizing-business-data-indexing.html) <br>
- [Test data quality at scale with Deequ](https://aws.amazon.com/blogs/big-data/test-data-quality-at-scale-with-deequ/) <br>
- [The What, Why, and When of Single-Table Design with DynamoDB](https://www.alexdebrie.com/posts/dynamodb-single-table/) <br>


## Chapter 6: Storage

- [Data orientation](https://en.wikipedia.org/wiki/Data_orientation) <br>
- [Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/) <br>
- [Diving Into Delta Lake: Schema Enforcement & Evolution](https://www.databricks.com/blog/2019/09/24/diving-into-delta-lake-schema-enforcement-evolution.html) <br>
- [Hot Data vs. Cold Data: Why It Matters?](https://www.alibabacloud.com/blog/hot-data-vs--cold-data-why-it-matters_595689) <br>
- [Rowise vs Columnar Database? Theory and in Practice](https://mangatmodi.medium.com/rowise-vs-columnar-database-theory-and-in-practice-53f54c8f6505) <br>
- [What is a Vector Database & How Does it Work? Use Cases + Examples](https://www.pinecone.io/learn/vector-database/) <br>
- [What is Object Storage? A Definition and Overview](https://www.lastweekinaws.com/blog/what-is-object-storage-a-definition-and-overview/) <br>
- [The What, Why, When, and How of Incremental Loads](https://www.timmitchell.net/post/2020/07/23/incremental-loads/) <br>



## Chapter 7: Ingestion

- [Airbyte's Sync Modes](https://docs.airbyte.com/platform/using-airbyte/core-concepts/sync-modes) <br>
- [Introduction to Apache Flink](https://www.oreilly.com/library/view/introduction-to-apache/9781491977132/ch06.html) <br>
- [The Dataflow Model: A Practical Approach to Balancing Correctness, Latency, and Cost in Massive-Scale, Unbounded, Out-of-Order Data Processing](https://research.google/pubs/the-dataflow-model-a-practical-approach-to-balancing-correctness-latency-and-cost-in-massive-scale-unbounded-out-of-order-data-processing/) <br>
- [Streaming pipelines](https://docs.cloud.google.com/dataflow/docs/concepts/streaming-pipelines) <br>
- [Snapshot window](https://learn.microsoft.com/en-us/stream-analytics-query/snapshot-window-azure-stream-analytics) <br>

## Chapter 8: Queries, Modeling, and Transformation

- [Building a Real-Time Data Vault in Snowflake](https://www.snowflake.com/en/developers/guides/vhol-data-vault/) <br>
- [Data Vault — An Overview](https://medium.com/snowflake/data-vault-an-overview-27bed8a1bf9f) <br>
- [Data Vault 2.0 Modeling Basics](https://www.red-gate.com/blog/data-vault-series-data-vault-2-0-modeling-basics/) <br>
- [A Detailed Guide on SQL Query Optimization](https://www.analyticsvidhya.com/blog/2021/10/a-detailed-guide-on-sql-query-optimization/) <br>
- [Difference between Kimball and Inmon](https://www.geeksforgeeks.org/dbms/difference-between-kimball-and-inmon/) <br>
- [Eventual vs Strong Consistency in Distributed Databases](https://hackernoon.com/eventual-vs-strong-consistency-in-distributed-databases-282fdad37cf7) <br>
- [The Evolution of the Corporate Information Factory](https://www.ewsolutions.com/evolution-corporate-information-factory/) <br>
- [Using cached query results](https://docs.cloud.google.com/bigquery/docs/cached-results) <br>
- [Cannot combine fields due to fan-out issues?](https://docs.holistics.io/docs/faqs/fan-out-issue) <br>
- [How a SQL Database Engine Works](https://medium.com/@grepdennis/how-a-sql-database-engine-works-c67364e5cdfd) <br>
- [How Should Organizations Structure their Data?](https://towardsdatascience.com/how-should-organizations-structure-their-data-c19b66d629e/) <br>
- [Inmon or Kimball: Which approach is suitable for your data warehouse?](https://www.computerweekly.com/tip/Inmon-or-Kimball-Which-approach-is-suitable-for-your-data-warehouse) <br>
- [Introduction to Data Vault Modeling](https://kentgraziano.com/wp-content/uploads/2012/02/introduction-to-data-vault-modeling.pdf) <br>
- [Introduction to Data Warehousing](https://moi.vonos.net/programming/dwh-intro/) <br>
- [Introduction to Data Vault for Data Warehousing](https://moi.vonos.net/programming/dwh-datavault/) <br>
- [Dimensional Modeling Techniques](https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/kimball-techniques/dimensional-modeling-techniques/) <br>
- [Modeling of real-time streaming data?](https://stats.stackexchange.com/questions/898/modeling-of-real-time-streaming-data) <br>
- [The New “Unified Star Schema” Paradigm in Analytics Data Modeling Review](https://towardsdatascience.com/the-new-unified-star-schema-paradigm-in-analytics-data-modeling-review-a245b2641dc8/) <br>
- [Slowly Changing Dimensions](https://www.oracle.com/webfolder/technetwork/tutorials/obe/db/10g/r2/owb/owb10gr2_gs/owb/lesson3/slowlychangingdimensions.htm) <br>
- [Corporate Information Factory](https://www.sciencedirect.com/topics/computer-science/corporate-information-factory) <br>
- [Types of Data Warehousing Architecture](https://medium.com/@amritha_fernando/types-of-data-warehousing-architecture-9a656443b510) <br>
- [Method and apparatus for functional integration of metadata US patent](https://patentimages.storage.googleapis.com/11/76/df/b9bcd21d6a9433/US8972463.pdf) <br>
- [Bill Inmon Data Warehouse](https://www.zentut.com/data-warehouse/bill-inmon-data-warehouse/) <br>



## Chapter 9: Serving Data for Analytics, Machine Learning, and Reverse ETL

- [Data Mesh](https://www.oreilly.com/library/view/data-mesh/9781492092384/) <br>
- [How to Quickly Anonymize Personal Names in Python](https://towardsdatascience.com/how-to-quickly-anonymize-personal-names-in-python-6e78115a125b/) <br>
- [Data Mesh Principles and Logical Architecture](https://martinfowler.com/articles/data-mesh-principles.html) <br>
- [Self-Service Business Intelligence: Dissolving the Barriers to Creative Decision-Support Solutions](https://www.forrester.com/blogs/10-01-11-self_service_business_intelligence_dissolving_the_barriers_to_creative_decision_support_solutions/) <br>
- [Fundamentals of Self-Service Machine Learning](https://www.dataversity.net/articles/fundamentals-of-self-service-machine-learning/) <br>
- [The future of BI is Headless](https://medium.com/gooddata-developers/the-future-of-bi-is-headless-e3949bb0bf2) <br>
- [How to Build Great Data Products](https://hbr.org/2018/10/how-to-build-great-data-products) <br>
- [Know Your Customers’ “Jobs to Be Done”](https://hbr.org/2016/09/know-your-customers-jobs-to-be-done) <br>
- [The missing piece of the modern data stack](https://benn.substack.com/p/metrics-layer) <br>
- [Understanding the Superset Semantic Layer](https://preset.io/blog/understanding-superset-semantic-layer/) <br>
- [Self-Service Analytics: What, Why, and How?](https://www.gooddata.com/blog/what-selfservice-analytics-bi-really-means/) <br>
- [What Is Real-Time Analytics?](https://startree.ai/resources/what-is-real-time-analytics/) <br>




## Chapter 10: Security and Privacy

- [Building Secure and Reliable Systems](https://www.oreilly.com/library/view/building-secure-and/9781492083115/) <br>
- [OWASP](https://owasp.org/) <br>
- [Practical Cloud Security](https://www.oreilly.com/library/view/practical-cloud-security/9781492037507/) <br>


