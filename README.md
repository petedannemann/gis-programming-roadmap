# Definitive Guide to GIS Programming
<p align="center">
  <img src="https://gisgeography.com/wp-content/uploads/2016/03/gis-programming-in-python-678x322.png" alt="Image of Coding">
</p>

<p align="center">
  <strong>Under development</strong>
</p>

## Table of Contents
- [Intro](#intro)
- [GIS Fundamentals](#gis-fundamentals)
- [Intro to CS](#intro-to-cs)
- [Data Analysis with Python](#data-analysis-with-python)
- [GIS Programming with Python](#gis-programming-with-python)
- [Databases & SQL](#databases-&-sql)
- [Spatial SQL](#spatial-sql)
- [Version Control](#version-control)
- [Web Development Fundamentals](#web-development-fundamentals)
- [Web GIS](#web-gis)
- [Front End Libraries](#front-end-libraries)

## Intro
This repository compiles resources that will take a motivated user from GIS noob to a proficient GIS Developer. The sections articles are organized by skill level and meant to be progressed through subsequentially. This was highly inspired by [Open Source Society University](https://github.com/ossu/computer-science#introduction-to-computer-science).

Resources mostly come from highly effective and free cources as well as blog posts and tutorials. There is a mixture of proprietary (ESRI) and open-source materials.

Please feel free to contribute and correct any errors that I inevitably will make.

## GIS Fundamentals

If you've taken an intro to GIS course or used GIS in the workplace for more than a few months, skip this section. Otherwise, let's review some materials to make sure we have a basic understanding of what GIS is, what common GIS tasks are, and what GIS tools exist out there.

Choose one of desktop softwares below and run through the associated course to get up to speed. This will take about 40 hours and will give you a great foundation in GIS. 

##### ArcMap / ArcPro
ArcMap and ArcPro are proprietary desktop software for performing GIS analysis distributed by ESRI. These are the most widely used in the industry and learning them is the safest bet at dipping your feet into the industry. Getting to Know ArcPro comes with a free one-year ArcPro license and is well worth the money if you are serious about entering the field. If you take an intro to GIS course through a college, chances are you'll run through this book as a majority of your course work.

##### QGIS
The most commonly used open source desktop software. It is free to download and has a wide array of plugins that let you do just about anything with GIS.

| Courses (Choose one)                                                                                                     | Difficulty | GIS Software |
|--------------------------------------------------------------------------------------------------------------------------|------------|--------------|
| [Getting to Know ArcPro](https://esripress.esri.com/display/index.cfm?fuseaction=display&websiteID=229&moduleID=0) ($40) | Easy       | ArcPro       |
| [Official QGIS Tutorial](https://docs.qgis.org/2.8/en/docs/training_manual/foreword/index.html)                          | Easy       | QGIS         |

##### Reading (Optional)
[GIS Fundamentals: GIS Fundamentals: A First Text on Geographic Information Systems](https://www.amazon.com/GIS-Fundamentals-Geographic-Information-Systems/dp/0971764735)

## Intro to CS
Learn basics of programming. How much you enjoy one of these courses may be a good indicator of your success in programming.

| Courses (Choose One)                                                                                                                                        | Difficulty | Languages                              |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|----------------------------------------|
| [Introduction to Computer Science and Programming using Python](https://www.edx.org/course/introduction-to-computer-science-and-programming-using-python-0) | Medium     | Python                                 |
| [CS50: Introduction to Computer Science](https://online-learning.harvard.edu/course/cs50-introduction-computer-science)                                                                               | Hard       | C, PHP, JavaScript, SQL, CSS, and HTML |

## Data Analysis with Python
Learn how to use popular data analysis libraries in Python such as Numpy and Pandas. I'm listing quite a few paid options here because they are of very high quality and are interactive.

| Resource (Choose one)                                                                                         | Difficulty |
|---------------------------------------------------------------------------------------------------------------|------------|
| [Geo Python](https://geo-python.github.io/2018/)                                                              | Medium     |
| [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)                          | Medium     |
| [Python for Data Analysis](https://www.amazon.com/Python-Data-Analysis-Wrangling-IPython/dp/1449319793) ($28) | Medium     |
| [Dataquest](https://www.dataquest.io/) ($23 - $50 / month)                                                    | Medium     |
| [Data Camp](https://www.datacamp.com/) ($25 - $30 / month                                                     | Medium     |
| [Brandon Rhoades Pandas Tutorial](https://www.youtube.com/watch?v=5JnMutdy6Fw&feature=youtu.be)               | Medium     |

## GIS Programming with Python
Learn how to write scripts to perform GIS analyses and automate repetetive tasks with Python.

| Courses (Choose One)                                                                                  | Difficulty                        | GIS Software |
|-------------------------------------------------------------------------------------------------------|-------------------------------------|------------|
| [GEOG 485: GIS Programming and Software Development](https://www.e-education.psu.edu/geog485/node/91) | Medium                | ArcGIS / ArcPy     |
| [Automating GIS Processes](https://automating-gis-processes.github.io/2018/)                         | Medium | GDAL, OGR, GeoPandas, Shapely, QGIS     |

##### Recommended - Continuation of GIS 485 
| Course                                                                                             | Difficulty                                                        | GIS Software |
|----------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|------------|
| [GEOG 489: Advanced Python Programming for GIS](https://www.e-education.psu.edu/geog489/node/1776) | Medium  | ArcPy, Jupyter Notebook, Esri ArcGIS API for Python, QGIS, GDAL/OGR    |

##### Readings (Optional)
- [Python Scripting for ArcGIS](https://esripress.esri.com/display/index.cfm?fuseaction=display&websiteID=276&moduleID=0) (ESRI)
- [Geoprocessing with Python](https://www.manning.com/books/geoprocessing-with-python) (Open Source)

## Databases & SQL
Learn how to query data, make tables and views, and perform data analysis with databases.

| Courses (Choose one)                                                                                  | Difficulty                                  | Database Engine |
|-------------------------------------------------------------------------------------------------------|--------------------------------------------------|------------|
| [SQL Zoo](https://sqlzoo.net/)                                                                        | Medium | SQL Server, Oracle, MySQL, DB2,  and  PostgreSQL     |
| [Stanford - Introduction to Databases](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about) | Hard                                          | Unknown       |
| [CS145: Data Management and Data Systems](https://cs145-fa18.github.io/course_info.html)              | Hard                                  | Google BigQuery       |

## Spatial SQL
Learn how to store GIS data and manipulate it in a database.

| Courses (Choose one)                                                                                                                    | Difficulty      | Database Engine |
|-----------------------------------------------------------------------------------------------------------------------------------------|----------------------|------------|
| [GEOG 868 - Spatial Database Management](https://www.e-education.psu.edu/spatialdb/node/1776)                                           | Medium | PostgreSQL / PostGIS      |
| [Boundless - Intro to PostGIS](https://web.archive.org/web/20170913113658/http://workshops.boundlessgeo.com/postgis-intro/welcome.html) | Medium | PostgreSQL / PostGIS      |
| [CS145: Data Management and Data Systems](https://cs145-fa18.github.io/course_info.html)                                                | Hard      | Google BigQuery       |

## Version Control
Learn how to manage projects using version control.

| Resource (Choose one)                                      | Software | Difficulty |
|------------------------------------------------------------|----------|------------|
| [Offical Documentation](https://git-scm.com/doc)           | Git      | Medium     |
| [Offical Resources](https://try.github.io/)                | Git      | Medium     |
| [Git Tutorial by Atlassian](https://www.atlassian.com/git) | Git      | Medium     |

## Web Development Fundamentals
Learn the basics of web development. It's very important to do this before trying to jump into web GIS.

| Courses (Choose one)                                                                                                            | Languages                             | Difficulty |
|---------------------------------------------------------------------------------------------------------------------------------|---------------------------------------|------------|
| [CS50: Web Programming with Python and JavaScript](https://www.edx.org/course/cs50s-web-programming-with-python-and-javascript) | Python, HTML, CSS, Javascript, SQL    | Medium     |
| [Colt Steele's Web Developer Bootcamp](https://www.udemy.com/the-web-developer-bootcamp/)                                       | Node.js, HTML, CSS, Javascript, NoSQL | Medium     |
| [The Odin Project](https://www.theodinproject.com/)                                                                             | Ruby, HTML, CSS, Javascript           | Medium     |

##### Recommended - Continuation of Colt Steele's Web Developer Bootcamp
| Courses (Choose one)                                                                                        | Languages                                  | Difficulty |
|-------------------------------------------------------------------------------------------------------------|--------------------------------------------|------------|
| [Colt Steele's Advanced Web Developer Bootcamp](https://www.udemy.com/the-advanced-web-developer-bootcamp/) | Javascript, NoSQL (MongoDB), React / Redux | Medium     |

## Web GIS
Learn how to add maps to your web applications.

| Courses (Choose one)                                                                                                     | Languages / Frameworks                        | Difficulty |
|--------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|------------|
| [GEOG 863 - Web Application Development for Geospatial Professionals](https://www.e-education.psu.edu/geog863/node/1776) | HTML, CSS, Javascript, ArcGIS Javascript API  | Easy       |
| [GEOG 585: Open Web Mapping](https://www.e-education.psu.edu/geog585/node/508)                                           | QGIS, GDAL, OGR, GeoServer, TileMill, Leaflet | Medium     |

## Front End Libraries
Learn how to make modern web applications using front end libraries.

| Courses (Choose one)                                                                                                                    | Framework / Library | Difficulty |
|-----------------------------------------------------------------------------------------------------------------------------------------|---------------------|------------|
| [Tyler Mcginnis: Free Online React BootCamp](https://tylermcginnis.com/free-react-bootcamp/)                                            | React               | Medium     |
| [Maximilian Schwarzmüller: Angular 7 (formerly Angular 2) - The Complete Guide](https://www.udemy.com/the-complete-guide-to-angular-2/) | Angular             | Hard       |
| [Maximilian Schwarzmüller: Vue JS 2 - The Complete Guide](https://www.udemy.com/vuejs-2-the-complete-guide/)                            | Vue                 | Easy       |
