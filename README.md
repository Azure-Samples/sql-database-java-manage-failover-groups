---
page_type: sample
languages:
- java
products:
- azure
extensions:
- services: Sql
- platforms: java
---

# Getting Started with Sql - Manage Sql Failover Groups - in Java #


  Azure SQL sample for managing SQL Failover Groups
   - Create a primary SQL Server with a sample database and a secondary SQL Server.
   - Get a failover group from the primary SQL server to the secondary SQL server.
   - Update a failover group.
   - List all failover groups.
   - Delete a failover group.
   - Delete Sql Server
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/sql-database-java-manage-failover-groups.git

    cd sql-database-java-manage-failover-groups

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.