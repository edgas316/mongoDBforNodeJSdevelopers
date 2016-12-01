# mongoDBforNodeJSdevelopers
### MongoDB installation on Windows
* Download MongoDB 
* Run installation
* cd to the mongoDB dirrectory
* create two more folders there ("log" and "data")
* inside of data create "db" folder
* then go to bin directory and run the following command: mongod --directoryperdb --dbpath C:\mongodb\data\db --logpath C:\mongodb\log\mongodb.log --logappend --rest --httpinterface --install
* net start MongoDB
* to run mongod shell: mongod
* to check the dbs run: db 
* to create and/or switch to db run: use dbname
* show dbs - will show all collections that has some data in it
* 
