cso_app
=======

syncing sqlite db with mysql


I have broken down the project to make things easier, i have only included a single table,
through the app i am making an insert into a sqlite DB, and on click of the sync icon all 
data in the sqliteDB is supposed to be sent to a mysql DB


Following are the two main activities in the app
------------------------------------------------

1.DBController--sqlite database creation
2.MainActivity--consisting of logic usedd to send data to external myslq DB
3.NewUser--activity am using to inserrt data into sqlite DB


Following are the four main PHP files on the API
------------------------------------------------ 

1.config.php - Configuration Variables i.e db host
2.db_connect.php - methods, open/close connection to mysql db
3.db_functions.php - methods performing DB operations specific to android app
4.insertdata.php - class called from inside android app to insert data in mysql db



Other parameters
-----------------
1.sqlite database name:
2.mysql database name:db_database
