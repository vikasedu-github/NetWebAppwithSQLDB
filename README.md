Type -1 .Net Core Web App (to see difference of types compare "ProductService.cs" under Service folder)
To Sucessfully run this app, We need to setup a DB server first on local system or Cloud and update serverURL, username, password & DB name in "ProductService.cs" under Service folder. 
It's not the right way to establish connection with DB because username & password is hard coded. There is another way to connect with DB using connection string and that app is 'NetWebAppwithSQLDBusingConnectionString' avavilable in repo.
