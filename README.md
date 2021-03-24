# SQL Server
This module overviews SQL Server fundamentals and skills to code using T-SQL  
**Pre-requisite:** Basic knowledge of RDBMS concepts and SQL   
**Expertise:** Entry level developer  

## SQL Server Overview 

### Microsoft SQL Server
Microsoft SQL Server is a database management and analysis platform for online transactions processing(OLTP), data warehousing and e-commerce applications.  

### SQL Server 2005 Components
- SQL Server Integreation Services
  - Reporting Services
  - Analysis Services
    - Notification Services
  - Database Engine
    - Notification Services
    - Full-text Search
    - Service Broker
    - Replication  
    
### SQL Server Tools
1. SQL Server Management Studio
2. SQL Server Business Intelligence Development Studio
3. SQL Server Profiler
4. SQL Server Configuration Manager
5. SQL Server Surface Area Configuration
6. Database Engine Tuning Advisor
7. Command Prompt Utilities

### SQL Server Authentication
SQL Server supports two types of authentication:  
- Windows Authentication
- SQL Server Authentication

### Databases
  - **Master**
    - It records all system-level information for an instance of SQL Server.
    - It records the existence of all other databases and the location of database files.
    - As *Master* records the initialization of SQL Server, SQL Server can't start if the master database is unavailable. 
  - **Model**
    - It applies as the template for all databases created on the instance of SQL Server.
    - Any modifications to the *Model* database will be applied to any databases created afterwards.
  - **MSDB**
	- It's applied by SQL Server Agent for scheduling alerts and jobs.
  - **Tempdb**
	- *Tempdb* is the separate workspace for holding temporary objects and intermediate result sets.
  - **Resource**
	- *Resource* is a read-only database consisting of copies of all system objects shipped with SQL Server.

## T-SQL or Transact SQL

### What is T-SQL?  
  - T-SQL is an *extension* of the SQL developed by Microsoft, which contains few additional transactional structures used to operate any of the SQL Server based relational databases.
  - This extension includes multiple *new characteristics* such as exception handling, string and date functions and other minor upgrades in the existing functions.
  - It yields high degree of manipulative *control in the hands of programmers*; thus, it can also be *easily integrated with business tools* like Dynamics and PowerBI.

### Types of T-SQL Commands
Any T-SQL/ SQL commands are classified in three types;  
- **DDL - Data Definition Language**:  Used to design and modify the structure of databases and it's objects 
	- CREATE
	- ALTER
	- DROP
- **DML - Data Manipulation Language**: To perform CRUD operations over databases/ objects  
	- INSERT
	- SELECT
	- UPDATE
	- DELETE
- **DCL - Data Control Language**: For controling the access of databases/objects
	- GRANT
	- REVOKE
	- DENY

\* Any user attempting to execute the commands must have permissions to execute respective commands.

### Data Integrity
- PRIMARY KEY
- FOREIGN KEY
- UNIQUE
- CHECK
- DEFAULT
- NOT NULL

## Annexure

#### NOTES
- The **Enterprise Manager** and **Query Analyzer** are the most important SQL Server tools replaced with ***SQL Server Management Studio (SSMS)***.  
- SQL Server uses **Command Line Utility tools** such as ***dta, bcp, sqlcmd, osl***.

#### DATATYPES
SQL Server supports the following datatypes, organized into certain categories as listed;  
- Approximate Numerics
	- float
	- real
- Binary Strings
	- binary
	- varbinary
	- image
- Character Strings
	- char
	- varchar
	- text
- Date and Time
	- datetime
	- smalldatetime
- Exact Numerics
	- bit
	- tinyint
	- smallint
	- int
	- bigint
	- decimal
	- numeric
	- smallmoney
	- money
- Unicode Character Strings
	- nchar
	- nvarchar
	- ntext
- Other Datatypes
	- cursor
	- sql_variant
	- table
	- timestamp
	- uniqueidentifier
	- xml
