# AWS Database Table Operations Lab

This repository contains the SQL scripts and procedural steps completed during the **AWS Database Table Operations** lab. The project demonstrates core Proficiency in managing relational databases using the MariaDB/MySQL monitor via an AWS EC2 Command Host.

## Objectives
* **Create:** Initialize new databases and define table schemas with specific data types (CHAR, ENUM, FLOAT, INT).
* **Alter:** Modify existing table structures, including renaming columns to fix schema errors.
* **Inspect:** Use metadata commands to verify database and table integrity.
* **Drop:** Securely delete tables and databases as part of environment cleanup.

## Tech Stack
* **Cloud:** Amazon Web Services (AWS)
* **Compute:** EC2 (Amazon Linux 2)
* **Database:** MariaDB / MySQL
* **Tooling:** AWS Systems Manager (Session Manager)

## Lab Tasks
1.  **Environment Setup:** Connected to a remote Command Host and authenticated with the MariaDB monitor.
2.  **Schema Definition:** Created a `world` database and a detailed `country` table with primary keys and constraints.
3.  **Data Integrity:** Corrected a misspelled column (`Conitinent` → `Continent`) using the `ALTER` statement.
4.  **Challenge Lab:** Independently designed and implemented a `city` table schema.
5.  **Cleanup:** Performed a full teardown of the database environment to follow AWS best practices for resource management.

---
