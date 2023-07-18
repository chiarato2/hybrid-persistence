# Hybrid Persistence for Java
- This is a personal project

## Overview
The Java Database Framework is a lightweight and flexible Java library designed to provide seamless persistence of information in both relational and non-relational databases. The framework currently supports MongoDB and PostgreSQL as the supported database systems.

## Features
- **Relational Database Support:** The framework offers robust support for persisting data in a relational database management system (RDBMS), specifically PostgreSQL. It leverages SQL queries and transactions to provide efficient data storage and retrieval.
- **Non-Relational Database Support:** The framework also provides support for storing data in a NoSQL database, specifically MongoDB. It utilizes MongoDB's document-oriented model, allowing for flexible and schema-less data storage.
- **Easy Configuration:** The framework offers a simple and intuitive configuration interface, making it easy to set up and connect to the desired databases. It provides options to define database connection properties, credentials, and other related settings.
- **Object-Relational Mapping (ORM):** The framework includes an ORM layer that simplifies the interaction between Java objects and the underlying databases. It allows developers to map Java classes to database tables or MongoDB collections, automating the process of data retrieval and persistence.
- **Extensibility:** The framework is designed with extensibility in mind, allowing developers to easily add support for other databases or customize existing functionality. It provides extension points and APIs to accommodate specific requirements.

## Getting Started
To use the Java Database Framework in your project, follow these steps:
1. Add the framework's JAR file to your project's classpath.
2. Configure the framework by providing the necessary database connection details in the configuration file.
3. Define your Java model classes and annotate them appropriately to specify the mapping to database tables or MongoDB collections.
4. Utilize the framework's APIs to perform CRUD operations, execute queries, and manage transactions.

## Future Development
The Java Database Framework is an ongoing project with plans for further enhancements and expansions, including:
- Support for additional databases, such as MySQL, Oracle ...
- Performance optimizations and scalability improvements.
- Advanced querying capabilities, including support for aggregation pipelines and SQL-like joins.

## Contributions
Contributions to the Java Database Framework project are welcome. If you encounter any issues, have suggestions, or would like to contribute code, please refer to the project's GitHub repository for more information.