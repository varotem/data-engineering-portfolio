# OLTP Database 

OLTP database is generally used to handle every day business transactions of an organization like a bank or a
super market chain. OLTP databases can be write heavy or may have a balanced read/write load.

An OLTP database is expected to handle a huge number of transactions per second. Each transaction usually
involves accessing (read/write) a small portion of the database, in other words the payload per transaction is
small. The time taken to execute a transaction usually called latency needs to be very less.

# Important Note on Designing OLTP Database

The schema of an OLTP database is higly normalized so as to achieve a very low latency. To further improve
the latency an OLTP database stores only the recent data like the last few week's data. They are usually run
on storage that is very fast like SSD.

# Scenario
Design a data platform that uses MySQL as an OLTP database to store the OLTP data for an E-Commerce Company.

# Tasks
- design the schema for OLTP database.
- load data into OLTP database.
- automate admin tasks.

# Tools & Software that will be used in this Project
- MySQL 8.0.22
- phpMyAdmin 5.0.4
