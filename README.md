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
  - **Tempdb**
  - **Resource**

### T-SQL or Transact SQL
#### What is T-SQL?  
  - T-SQL is an *extension* of the SQL developed by Microsoft, which contains few additional transactional structures used to operate any of the SQL Server based relational databases.
  - This extension includes multiple *new characteristics* such as exception handling, string and date functions and other minor upgrades in the existing functions.
  - It yields high degree of manipulative *control in the hands of programmers*; thus, it can also be *easily integrated with business tools* like Dynamics and PowerBI.

#### Types of T-SQL Commands

## Data Integrity 

#### NOTES
- The **Enterprise Manager** and **Query Analyzer** are the most important SQL Server tools replaced with ***SQL Server Management Studio (SSMS)***.  
- SQL Server uses **Command Line Utility tools** such as ***dta, bcp, sqlcmd, osl***.
