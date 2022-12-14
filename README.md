# SER531-Spring22-Team12

GitHub repo for SER 531 Spring 22 Team 12.

* Clone the repo git clone -b master https://github.com/ksharm53/SER-531-Team12.git

* YouTube Link: https://www.youtube.com/watch?v=FZ19ECeafi8

* Our project is hosted on: http://ser531team12project.devanshgajjar.com/
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
Installation of Anaconda on Windows
--------------------------------------------------------------------------------------------------------------------------------------------
- Steps:
- 1)Visit Anaconda.com/downloads
- 2)Select Windows
- 3)Download the .exe installer
- 4)Open and run the .exe installer
- 5)Open the Anaconda Prompt and run some Python code

- Open a Jupyter notebook with the Windows Start Menu:

One way to open a Jupyter notebook is to use the Windows Start Menu. Note that the Anaconda distribution of Python must be installed to use the Windows Start Menu to open a Jupyter notebook. 

Download Anaconda at the following link: Anaconda.com/distribution

Open the Windows start menu and select [Anaconda3(64 bit)] ???> [Jupyter Notebook]

Windows 10 Start Menu showing the Jupyter Notebook application

This action opens the Jupyter file browser in a web browser tab.

In the upper right select [New] ???> [Python 3]

Jupyter notebook file browser. Note a new Python 3 notebook is selected

A new notebook will open as a new tab in your web browser.

A newly opened Jupyter notebook

Try typing the code below in the first cell in the notebook to the right of the In [ ]: prompt:

import this
Then click the run button in the middle of the menu at the top of the notebook.

--------------------------------------------------------------------------------------------------------------------------------------------
Protege Tool Installation:
--------------------------------------------------------------------------------------------------------------------------------------------
- Click on the download link and download (http://protege.stanford.edu/products.php#desktop-protege)
- Navigate to the folder the application was downloaded
- Extract all folders from the compressed folders and select the destination folder 
- Double click on protege to launch protege
--------------------------------------------------------------------------------------------------------------------------------------------
How To Use:
--------------------------------------------------------------------------------------------------------------------------------------------
- Click on the provided link()
- The browser displays the main page and navigate to the button click to go to query page 
- It redirects to the page where it explains all the query filters and click on the respective query buttons to display the data according to the query functionality
--------------------------------------------------------------------------------------------------------------------------------------------
Testing using postman:
--------------------------------------------------------------------------------------------------------------------------------------------
- Navigate to Postman application
- Copy the respective webserver url and paste it in postman and change the method type to GET
- Navigate to the params and insert value as SPARQL query
- The data will be diplayed in the body 

 --------------------------------------------------------------------------------------------------------------------------------------------
 ##Changes since last deliverable
 
 There is no major changes since last submission. Owl file has been changed with new classes to accomodate with incremental changes. Rest of the functinality remains same.
 
