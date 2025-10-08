## pdb-project_Chris_Shyaka_27889
## Oracle Database PDB Management – Assignment Report

## Student Information

- **Name**: *Shyaka Chris*
- **Student ID**: *27889*
- **Username Used**: *Chris_plsqlauca_27889*

---

##  Overview

This assignment involves the creation, deletion, and management of Pluggable Databases (PDBs) using Oracle Database and Oracle Enterprise Manager (OEM). The tasks are designed to strengthen understanding of Oracle Multitenant architecture, database user management, and Enterprise Manager configurations.

---

##  Task 1: Create a New Pluggable Database (PDB)
- **Purpose**: This account will be used to store all course-related work.

###  Steps Performed:
1. Logged into the CDB as SYSDBA.
2. Ran SQL command to create the PDB.
3. Opened the PDB.
4. Created the user and granted necessary privileges.

###  Screenshot: PDB Creation

> *(<img width="496" height="291" alt="pluggable database" src="https://github.com/user-attachments/assets/cccdce6a-6893-4961-9e1e-8d62695f71b4" />
)*

---

##  Task 2: Create and Delete a PDB

###  Steps Performed:
1. Created a new PDB using SQL command.
2. Verified the PDB creation using `SHOW PDBS`.
3. Closed and dropped the PDB using appropriate commands.

###  Screenshot: PDB Creation

> *(<img width="523" height="92" alt="create and delete pdb" src="https://github.com/user-attachments/assets/e83af910-a497-42cd-a5a1-6a91ecffaa12" />
)*

###  Screenshot: PDB Deletion

> *(<img width="536" height="243" alt="evidence of completion" src="https://github.com/user-attachments/assets/2e383510-1660-4c98-afb9-e2fec4d62115" />
)*

---

##  Task 3: Oracle Enterprise Manager (OEM) Setup

###  Steps Performed:
1. Configured OEM with database connection.
2. Ensured visibility of created PDB and user account.
3. Verified monitoring of DB activity and user sessions.
### Screenshoot: Evidence of Completion 

> *(<img width="385" height="131" alt="OEM conf evidence of comp" src="https://github.com/user-attachments/assets/0d3b281b-6748-46b3-bde2-af91447168c8" />
)*
###  Screenshot: OEM Dashboard

> *(<img width="960" height="475" alt="evidence of completion last" src="https://github.com/user-attachments/assets/8d5337ab-974a-4dc3-9192-7bfeb745cd4a" />
)*

---

## Issues Faced & How I resolved Them

- **Issue 1**: *Encountered ORA-xxxx error while creating PDB.*
  - **Solution**: Ensured that the database had sufficient storage and the default tablespace was set properly.

- **Issue 2**: *OEM not loading initially.*
  - **Solution**: Restarted the `emctl` service and reconfigured the listener.


---

##  Conclusion

Successfully completed all tasks including the creation and deletion of PDBs and OEM configuration. The assignment reinforced concepts of multitenant database architecture and provided hands-on experience with administrative tasks in Oracle.




