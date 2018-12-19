# MvcMovie
To run this project, open the project with visual studio;

change "connectionStrings"in web.config as following:
1. make sure "Data Source" and your local SQL server has the SAME NAME!!
2. make sure "AttachDbFilename" has the right local path for database file,which you can find in folder "App_Date". (or you can try "AttachDbFilename=|DataDirectory|\Movies.mdf", it should work, but I dont know why, it doesnt work in my computer)
