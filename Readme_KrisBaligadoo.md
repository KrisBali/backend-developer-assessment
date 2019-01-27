1. Pull request contains 4 zipped files + this readme.

	[SQL script.zip]
	1st - Script to create database, two tables and insertion of data.
	
	[ArtistWebApi.zip / z01 /z02 (3 splitted zip files)]
	2nd - Visual studio solution containing 5 projects
			Artist (the web api)
			Artist.Business (Business logic layer)
			Artist.Data (Data Layer / Entity)
			Artist.Domain (Domain layer)
			Artist.xUnitTests	(Contains xUnit tests)

2. Run script versus local database to create database, tables and populate them.

3. Modify connection strings in project to point to correct database. 
(currently on local)

4. Build projects in solution.

5. Publish webapi and setup in IIS server.

6. Test project included in solution under Artist.xUnitTests.

7. Thank you.