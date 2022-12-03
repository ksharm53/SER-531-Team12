# SER531-Spring22-Team12

GitHub repo for SER 531 Spring 22 Team 12.

* Clone the repo git clone -b master https://github.com/ksharm53/SER-531-Team12.git


--------------------------------------------------------------------------------------------------------------------------------------------
Authors
--------------------------------------------------------------------------------------------------------------------------------------------
- Nihal Singh (1223932476)
- Kanav Sharma (1222257920)
- Virinchi (1223592279)
- Krishna Pandya (1222546520)
- Jay Patel (1224303457)

--------------------------------------------------------------------------------------------------------------------------------------------
Installation
--------------------------------------------------------------------------------------------------------------------------------------------
##Fuseki Server Setup
- Create Free Tier AWS setup and account.
- Create and EC2 Instance with t2 micro flavor in us-east-1 region
- Login to EC2 either through console OR login through SSH (you will get ssh keys while creating instance and same can be used for login).
- Install Java
```$ sudo apt-get update
$ sudo apt-get install openjdk-8-jdk
$ java -version```
```
- Download Fuseki
```$ mkdir opt
$ cd opt
$ mkdir fuseki
$ cd fuseki
$ wget http://mirror.reverse.net/pub/apache/jena/binaries/apache-jena-fuseki-3.9.0.tar.gz
$ tar -xvzf apache-jena-fuseki-3.9.0.tar.gz
$ rm apache-jena-fuseki-3.9.0.tar.gz
$ cd apache-jena-fuseki-3.9.0
# For convenience, we set an environment variable....
$ export FUSEKI_BASE=$(pwd)
```
- Fuseki server is good to use post adding data set
```
$ ./fuseki-server
```




 --------------------------------------------------------------------------------------------------------------------------------------------
