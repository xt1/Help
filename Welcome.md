<properties date="2016-05-10"
SortOrder="1"
/>

![](images/devnet_logo.png) ![](expander-sdk.jpg)
Expander SDK: Server Data .net API
==================================

Documentation for NetServer 7.5
(Feb 2014)

The SuperOffice Server Data API provides .net programmers with direct access to the database through four different abstractions. Web services are built in a separate API on top of these classes.

From the most abstract to the most specific, the layers inside the Data API are:

1. [Archive Providers](Developer's%20Guide/Archives/Archives.htm) returns a search-result as a table. This hides the underlying database structure and presents a flattened, de-normalized view of the data.
2. [Entities](Developer's%20Guide/Entities/Entities.htm) load and save several related rows as a unit. This hides the details of the relationships in the database, while exposing the relationships as object properties and collections.
3. [Rows](Developer's%20Guide/Rows/Rows.htm) load and save single rows from the database. This is a traditional persistence layer. You must be aware of the database details of how table relationships are implemented when working at this level.
4. [OSQL](Developer's%20Guide/OSQL/OSQL.htm) is our objectified SQL, which provides database independence. Instead of writing SQL strings, you use objects to build your query. The objects generate SQL suitable for the database you are connected to.

Please explore what is available in this part of the SDK:
* [What's new in NetServer](What's%20new/What's%20new.htm)
* [Introduction to NetServer concepts](Introduction/Introduction.htm)
* [In depth guide to programming with NetServer](Developer's%20Guide/Developer's%20Guide.htm)
* [Programming examples](Examples/Examples.htm)

<!-- -->

* [Quote Connector APIs](Developer's%20Guide/ERP%20Connectors/ERP%20Quote%20Connector%20Interface/ERP%20Quote%20Connector%20Interface.htm) to support integration with price lists and quote management systems.
* [ERP Sync Connector APIs](Developer's%20Guide/ERP%20Connectors/ERP%20Sync%20Connector%20Interface/ERP%20Sync%20Connector%20Interface.htm) to support customer and project integration with ERP systems.
