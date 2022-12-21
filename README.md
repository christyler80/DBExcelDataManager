# DB Excel Data Manager
DB Excel Data Manager is built using Microsoft Excel and allows data from SQL Database tables to be viewed, added and edited using 
Excel Worksheets. Database table schema details can also be viewed. 

DB Excel Data Manager is distributed in the hope that it will be useful for assisting with database systems administration and 
legacy application automation (e.g., for regression testing).

To get started, download the DB_DataManager.xlsb workbook and Northwind.accdb into a folder and open the workbook.

Important: All data changes are always the responsibility of the user(s) and must be checked thoroughly by the user(s), both 
before being applied to the database and after the databases updates have been completed. It is strongly recommended 
that data backups are taken before any data changes are applied. 

DB Data Manager is free and open-source software: you can redistribute it and/or modify it under the terms of the GNU 
General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) 
any later version. 

DB Data Manager is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY, without even the 
implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License 
for more details. 

The project files with source code can be found at https://github.com/christyler80/DB_DataManager. 

DB Data Manager requires Microsoft Excel 2016 or later and supports SQL Server, SQLite, ODBC (32bit) and Microsoft 
Access. 

Basic testing has been undertaken using the Northwind and Pubs databases running on SQL Server, SQLite, 
MySQL/MariaDB and Microsoft Access. 

Where possible, please use Northwind or Pubs database examples to report any errors and/or feature requests. 

Important: At this time: 

	PuttyDriver will only work with 32-bit versions of Microsoft Excel 2016 or later. 

	Microsoft Excel 64-bit versions are not currently supported. 

	32-bit or 64-bit versions of Microsoft Windows 10 or Windows 11 operating system are supported. 

	Most text and numeric field data types are supported. 

	Binary data and other non-text or non-numeric field types are not supported. 

	Data must be entered with correct formatting and numeric scale/precision (e.g., number of decimal places). 

	DB Data Manager should work on Windows 7, but this has not been tested. 

	Other operating systems (e.g., Apple, Linux) are not supported

