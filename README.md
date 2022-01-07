# 2021 S2 ISYS2120 - DB Application Programming Project

### Overview

A media server written in Flask and SQL. The media server is designed to keep track of files and metadata information regarding various audio and video media. Log in and dive into the diverse media (podcast, TV show, movie, music). 
 
### Acknowledgement for the base code : 

- The code is designed for the University of Sydney, School of Computer Sciences
- Initial Codebase by Harshana Randeni
- Initial Schema by Ryan Skelton 

### Getting Started (from assignment helperslides) 

##### 1. Download the code base or clone it from the GitHub repository and unzip it into a local directory

##### 2. Update `config.ini` 

Since this program used local database, `DATABASEREMOTE` section in `config.ini` is unnecessary. 

##### 3. Use a postgres client to open and run ‘mediaserver-schema.sql’

##### 4. Use a postgres client to open and run ‘mediaserver-sampledata.sql’

##### 5. To Run 

####### On windows, 

- Install Windows Subsystem for Linux(WSL)
- Open a bash terminal
- Run `./run.command`

####### On Mac/Linux

- Run `./run.command`

##### 6. Open `127.0.0.1:5000` on a browser to access the webserver client side 

