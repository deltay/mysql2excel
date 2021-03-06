mysql2excel
=============

Command-line tool to dump MySQL tables to Microsoft Excel .xlsx Spreadsheets written
in Java.


## Downloading

Download the latest release from https://github.com/DevDungeon/mysql2excel/releases
or clone the repo from https://github.com/DevDungeon/mysql2excel
    
    git clone https://github.com/DevDungeon/mysql2excel

    # Compile and package with Maven
    cd mysql2excel
    mvn package

## Usage

### Print help information

    java -jar mysql2excel-1.0.1.jar

### Generate a settings template file

    java -jar mysql2excel-1.0.1.jar -g sample.config

### Dump from MySQL to Excel using settings in config file

    java -jar mysql2excel-1.0.1.jar my.config


## Project Page

* https://www.devdungeon.com/content/mysql2excel
* https://www.github.com/DevDungeon/mysql2excel

## Contact

NanoDano <nanodano@devdungeon.com>


## Changelog

* 2018-03-25 v1.0.1
    * Bug fix: added convert zeroDateTimeBehavior to convertToNull, minor formatting tweaks
* 2018-03-18 v1.0.0
    * Initial stable release

## To do

* Allow multiple tables or all tables to be dumped at once
* Allow custom SQL query to be run
