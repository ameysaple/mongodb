# MongoDB Documentation

## Install Mongo DB Community Server (Windows)

Download [Mongo DB Community Server](https://www.mongodb.com/dr/fastdl.mongodb.org/win32/mongodb-win32-x86_64-2008plus-ssl-3.6.4-signed.msi/download)

* **After Installing**  => *go to installed path*

##Create Directory **data/db** & **log**

*	**data/db** => database storage
* 	**log** => log files

###Go to bin 

```
mongod --directoryperdb --dbpath C:\mongodb\data\db --logpath C:mongodb\log\mongo.log --logappend --install
```

* *Start MongoDB Service*

```
net start MongoDB
```

### Start Mongo Shell

```
mongo
```
-------------------------------
#LIST OF Mongo DB Commands

##SHOW DATABASES
```
show dbs
```





