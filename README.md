# Awesome Cassandra [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![Buy Me A Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://tinyurl.com/2h9aktmd) &nbsp; [![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://tinyurl.com/d4xnrptz) &nbsp; [![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://tinyurl.com/mr22naua) &nbsp; [![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3)

> A curated list of awesome libraries, tools, frameworks, and resources for Apache Cassandra, a highly scalable, distributed NoSQL database designed for handling large amounts of data across many commodity servers.

## Contents

- [Libraries and Clients](#libraries-and-clients)
- [GUI Tools](#gui-tools)
- [Backup and Migration](#backup-and-migration)
- [Optimization and Monitoring](#optimization-and-monitoring)
- [Replication and Clustering](#replication-and-clustering)
- [Data Modeling and Design](#data-modeling-and-design)
- [Learning Resources](#learning-resources)
- [Books](#books)
- [Community](#community)
- [Contribute](#contribute)
- [License](#license)

## Libraries and Clients

- [DataStax Java Driver](https://github.com/datastax/java-driver) - The official Java driver for Apache Cassandra by DataStax.
- [Python Cassandra Driver (cassandra-driver)](https://github.com/datastax/python-driver) - The official Python driver for Apache Cassandra.
- [Node.js Cassandra Driver](https://github.com/datastax/nodejs-driver) - The official Node.js driver for Apache Cassandra.
- [GoCQL](https://github.com/gocql/gocql) - A native Go driver for Apache Cassandra.
- [Cassandra JDBC Driver](https://github.com/datastax/cassandra-jdbc) - A JDBC driver for connecting to Apache Cassandra.
- [Phantom](https://github.com/outworkers/phantom) - A Scala driver and DSL for Apache Cassandra.

## GUI Tools

- [DataStax Studio](https://www.datastax.com/products/datastax-studio) - A web-based development environment for Apache Cassandra and DataStax.
- [TablePlus](https://tableplus.com/) - A modern, native GUI tool for PostgreSQL, MySQL, and Cassandra.
- [DBeaver](https://dbeaver.io/) - A universal database tool that supports Apache Cassandra.
- [DBVisualizer](https://www.dbvis.com/) - A database management tool that supports Apache Cassandra.
- [NoSQL Workbench](https://aws.amazon.com/nosql-workbench/) - A visual design tool for NoSQL databases, including support for Apache Cassandra.

## Backup and Migration

- [Cassandra Backup Guide](https://cassandra.apache.org/_/backup_restore.html) - Official documentation on backup and restore strategies for Apache Cassandra.
- [Cassandra Snapshot](https://cassandra.apache.org/_/snapshots.html) - The built-in snapshot feature for backing up Cassandra tables.
- [Medusa](https://github.com/thelastpickle/cassandra-medusa) - A backup and restore tool for Apache Cassandra.
- [Apache Sqoop](https://sqoop.apache.org/) - A tool for migrating data between Apache Cassandra and relational databases.
- [Cassandra Migration](https://github.com/adolfojunior/cassandra-migration) - A database migration tool for Apache Cassandra, inspired by Flyway.

## Optimization and Monitoring

- [nodetool](https://cassandra.apache.org/doc/latest/tools/nodetool.html) - A built-in command-line tool for monitoring and managing Cassandra nodes.
- [Cassandra Reaper](https://github.com/thelastpickle/cassandra-reaper) - A tool for managing and scheduling repairs in Apache Cassandra.
- [Prometheus and Grafana](https://prometheus.io/) - Use Prometheus for metrics collection and Grafana for visualizing Cassandra performance.
- [Dynatrace](https://www.dynatrace.com/) - An application performance monitoring tool with support for Apache Cassandra.
- [New Relic](https://newrelic.com/) - A monitoring and observability platform with plugins for Cassandra.

## Replication and Clustering

- [Cassandra Replication](https://cassandra.apache.org/doc/latest/architecture/replication.html) - Official documentation on data replication in Cassandra.
- [Cassandra Clustering](https://cassandra.apache.org/doc/latest/architecture/distributed.html) - An overview of Cassandra's distributed architecture and clustering capabilities.
- [Cassandra Multi-DC Replication](https://cassandra.apache.org/doc/latest/architecture/multidc.html) - Best practices for setting up multi-data center replication in Cassandra.
- [Cassandra Sidecar](https://github.com/datastax/cassandra-sidecar) - A sidecar project for Apache Cassandra, providing additional operational capabilities.
- [Elassandra](https://github.com/strapdata/elassandra) - A fork of Cassandra that integrates Elasticsearch for real-time search and analytics.

## Data Modeling and Design

- [Data Modeling Guide](https://cassandra.apache.org/doc/latest/data_modeling/) - Official documentation on data modeling best practices in Apache Cassandra.
- [Cassandra Query Language (CQL)](https://cassandra.apache.org/doc/latest/cql/index.html) - The official reference guide for the Cassandra Query Language.
- [Cassandra Anti-Patterns](https://cassandra.apache.org/doc/latest/data_modeling/anti-patterns.html) - Common mistakes to avoid in Cassandra data modeling.
- [NoSQLBench](https://github.com/nosqlbench/nosqlbench) - A benchmarking tool for modeling and performance testing in Apache Cassandra.
- [Cassandra Schema Design Tips](https://www.datastax.com/blog/cassandra-schema-design-best-practices) - A guide to designing efficient schemas in Cassandra.

## Learning Resources

- [Apache Cassandra Documentation](https://cassandra.apache.org/doc/latest/) - The official Apache Cassandra documentation.
- [DataStax Academy](https://academy.datastax.com/) - Free courses and certifications for Apache Cassandra.
- [Cassandra Tutorial](https://www.tutorialspoint.com/cassandra/index.htm) - A comprehensive guide for learning Apache Cassandra.
- [Cassandra Blog](https://www.datastax.com/blog/category/cassandra) - Articles and tutorials on Apache Cassandra by DataStax.
- [The Last Pickle](https://thelastpickle.com/) - A blog with in-depth articles on Apache Cassandra.

## Books

- *Cassandra: The Definitive Guide* by Jeff Carpenter and Eben Hewitt - A comprehensive guide to Apache Cassandra.
- *Learning Apache Cassandra* by Mat Brown - A book focused on practical learning for Apache Cassandra.
- *Cassandra in Action* by Jeff Carpenter and Eben Hewitt - A practical book on building scalable applications with Apache Cassandra.
- *Mastering Apache Cassandra 3.x* by Nishant Neeraj - An advanced guide to mastering Apache Cassandra.
- *Effective Cassandra* by Russell Bradberry and Eric Lubow - A book on writing efficient and performant applications with Cassandra.

## Community

- [Apache Cassandra Mailing Lists](https://cassandra.apache.org/community/mailing_lists.html) - Official mailing lists for Apache Cassandra discussions.
- [Reddit: r/Cassandra](https://www.reddit.com/r/Cassandra/) - A subreddit for Apache Cassandra discussions and questions.
- [Stack Overflow: Cassandra](https://stackoverflow.com/questions/tagged/cassandra) - A Q&A site for Apache Cassandra-related questions.
- [Cassandra Slack](https://cassandra.apache.org/community/slack.html) - Join the Apache Cassandra Slack community for discussions and support.
- [Planet Cassandra](https://planetcassandra.org/) - A blog aggregator for Apache Cassandra news and updates.

## Contribute

Contributions are welcome!

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
