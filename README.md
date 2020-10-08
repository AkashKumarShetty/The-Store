# The-Store
************************************************************

### Authors:Akash Kumar Shetty, Siri Chandrashekar

### Assignments Features:
1.Database Connectivity: IMPLEMENTED
2.AJAX Search :IMPLEMENTED
3.Trending Bar chart :IMPLEMENTED
4.Reports for Admin :IMPLEMENTED
5.Tweets for twitter API :IMPLEMENTED
6.Recommendations :IMPLEMENTED

Addition Features:
1.Advertisement :IMPLEMENTED

MySql Server :

1.Install the MySQL Server.
2.Download the mysql-connector-java-X.X.X jar file.(version depends on your Sql server).
3.Place it to lib folder at location  'C:\apache-tomcat-7.0.34\lib'.

Mongo DB Server :

1.Install the Mongo DB server.
2.Download the mongo-java-driver-X.X.X jar file.(version depends on your Mongo DB server).
3.Place it to lib folder at location  'C:\apache-tomcat-7.0.34\lib'.
4.Create the db folder inside the data folder in C directory.
5.Then goto 'C:\Program Files\MongoDB\Server\4.0\bin' folder and run the 'mongod' file.
6.And then at same location run the 'mongo' file.
7.Run the below commands:
	use CustomerReviews
	db.createCollection("myReviews")
	db.createCollection("Comments")
8.You can use db.myReviews.find() commands to find the reviews added to 'myReviews' collection.
9.You can use db.Comments.find() commands to find the reviews added to 'Comments' collection.

Data Analytics(Bar chart) Setup :

1.For data analytics you need to download gson-2.3.1 jar and json-20171018 jar.
2.Place this jar at 'C:\apache-tomcat-7.0.34\lib' folder.

Project Setup:

1.Download and unzip the Project file.
2.Place the Project folder inside the 'C:\apache-tomcat-7.0.34\webapps' folder.
3.Then goto 'C:\apache-tomcat-7.0.34\webapps\BestDeal\BestDeal-Web-Application-master\WEB-INF\classes' folder and compile all
java files using the Javac *.java command.(Provided you have setup the Javapath and Env variables)
4.Then goto 'C:\apache-tomcat-7.0.34\bin' folder and then open command promt and run the command 'startup'.This 
will start the Apache Tomcat server.
5.Go to browser and enter the 'http://localhost/BestDeal/BestDeal-Web-Application-master/' url.
