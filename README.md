# GIS Programming Roadmap
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
- [Databases](#databases)
- [Spatial SQL](#spatial-sql)
- [Version Control](#version-control)
- [ETL](#etl)
- [Web Development Fundamentals](#web-development-fundamentals)
- [Web GIS](#web-gis)
- [Front End Libraries](#front-end-libraries)
- [Backend Web Development](#backend-web-development)

## Intro
This repository lays out a path to take someone with no GIS experience to a proficient GIS Developer. The sections are organized by skill level and meant to be progressed through sequentially. This was highly inspired by [Open Source Society University](https://github.com/ossu/computer-science#introduction-to-computer-science).

Resources mostly come from highly effective and free courses as well as blog posts and tutorials. There is a mixture of proprietary (ESRI) and open-source materials.

Please feel free to contribute and correct any errors that I inevitably will make.

## GIS Fundamentals

If you've taken an intro to GIS course or used GIS in the workplace for more than a few months, skip this section. Otherwise, let's review some materials to make sure we have a basic understanding of what GIS is, what common GIS tasks are, and what GIS tools exist out there.

Choose one of desktop softwares below and run through the associated course to get up to speed. This will take about 40 hours and will give you a great foundation in GIS. 

##### ArcMap / ArcPro
ArcMap and ArcPro are proprietary desktop software for performing GIS analysis distributed by ESRI. These are the most widely used in the industry and learning them is the safest bet at dipping your feet into the industry. Getting to Know ArcPro comes with a free one-year ArcPro license and is well worth the money if you are serious about entering the field. If you take an intro to GIS course through a college, chances are you'll run through this book as a majority of your course work.

##### QGIS
The most commonly used open source desktop software. It is free to download and has a wide array of plugins that let you do just about anything with GIS.

<center>
  
| Courses (Choose one)                                                                                                     | Difficulty | GIS Software |
|--------------------------------------------------------------------------------------------------------------------------|------------|--------------|
| [Coursera GIS Specialization](https://www.coursera.org/specializations/gis) | Easy | ArcPro|
| [Getting to Know ArcPro](https://esripress.esri.com/display/index.cfm?fuseaction=display&websiteID=229&moduleID=0) ($40) | Easy       | ArcPro       |
| [Official QGIS Tutorial](https://docs.qgis.org/3.4/en/docs/training_manual/foreword/index.html)                          | Easy       | QGIS         |

</center>

##### Reading (Optional)
- [GIS Fundamentals: GIS Fundamentals: A First Text on Geographic Information Systems](https://www.amazon.com/GIS-Fundamentals-Geographic-Information-Systems/dp/0971764735)

## Intro to CS
Learn basics of programming. How much you enjoy one of these courses may be a good indicator of your success in programming.

<center>
  
| Courses (Choose One)                                                                                                                                        | Difficulty | Languages                              |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|----------------------------------------|
| [Introduction to Computer Science and Programming using Python](https://www.edx.org/course/introduction-to-computer-science-and-programming-using-python-0) | Medium     | Python                                 |
| [CS50: Introduction to Computer Science](https://online-learning.harvard.edu/course/cs50-introduction-computer-science)                                                                               | Hard       | C, PHP, JavaScript, SQL, CSS, and HTML |

</center>
  
## Data Analysis with Python
Learn how to use popular data analysis libraries in Python such as Numpy and Pandas. I'm listing quite a few paid options here because they are of very high quality and are interactive.

<center>
  
| Resource (Choose one)                                                                                         | Difficulty |
|---------------------------------------------------------------------------------------------------------------|------------|
| [Geo Python](https://geo-python.github.io/2018/)                                                              | Medium     |
| [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)                          | Medium     |
| [Python for Data Analysis](https://www.amazon.com/Python-Data-Analysis-Wrangling-IPython/dp/1449319793) ($28) | Medium     |
| [Dataquest](https://www.dataquest.io/) ($23 - $50 / month)                                                    | Medium     |
| [Data Camp](https://www.datacamp.com/) ($25 - $30 / month)                                                    | Medium     |
| [Brandon Rhoades Pandas Tutorial](https://www.youtube.com/watch?v=5JnMutdy6Fw&feature=youtu.be)               | Medium     |

</center>

## GIS Programming with Python
Learn how to write scripts to perform GIS analyses and automate repetetive tasks with Python.

<center>
  
| Courses (Choose One)                                                                                  | Difficulty                        | GIS Software |
|-------------------------------------------------------------------------------------------------------|-------------------------------------|------------|
| [GEOG 485: GIS Programming and Software Development](https://www.e-education.psu.edu/geog485/node/91) | Medium                | ArcGIS / ArcPy     |
| [Automating GIS Processes](https://automating-gis-processes.github.io/2018/)                         | Medium | GDAL, OGR, GeoPandas, Shapely, QGIS     |

</center>
  
##### Recommended Additional Courses
- [GEOG 489: Advanced Python Programming for GIS](https://www.e-education.psu.edu/geog489/node/1776)
- [Geographic Data Science](http://darribas.org/gds18/)
- [Python for GIS Progression Path](https://github.com/AlexArcPy/python-for-gis-progression-path)
- [Coursera: Spatial Data Science and Applications](https://www.coursera.org/learn/spatial-data-science)
- [Datacamp: Visualizing Geospatial Data in Python](https://www.datacamp.com/courses/visualizing-geospatial-data-in-python)

##### Readings (Optional)
- [Python Scripting for ArcGIS](https://esripress.esri.com/display/index.cfm?fuseaction=display&websiteID=276&moduleID=0) (ESRI)
- [Geoprocessing with Python](https://www.manning.com/books/geoprocessing-with-python) (Open Source)
- [GeoPySpark](https://github.com/locationtech-labs/geopyspark)
- [Introduction to Geospatial Data in Python](https://www.datacamp.com/community/tutorials/geospatial-data-python)

## Databases
Learn how to query data, make tables and views, and perform data analysis with databases.

<center>
  
| Courses (Choose one)                                                                                  | Difficulty                                  | Database Engine |
|-------------------------------------------------------------------------------------------------------|--------------------------------------------------|------------|
| [SQL Zoo](https://sqlzoo.net/)                                                                        | Medium | SQL Server, Oracle, MySQL, DB2,  and  PostgreSQL     |
| [Stanford - Introduction to Databases](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about) | Hard                                          | Unknown       |
| [CS145: Data Management and Data Systems](https://cs145-fa18.github.io/course_info.html)              | Hard                                  | Google BigQuery       |

</center>

##### Additional Tutorial
- [SqlAlchemy Tutorial](https://docs.sqlalchemy.org/en/latest/orm/tutorial.html)

## Spatial SQL
Learn how to store GIS data and manipulate it in a database.

<center>
  
| Courses (Choose one)                                                                                                                    | Difficulty      | Database Engine |
|-----------------------------------------------------------------------------------------------------------------------------------------|----------------------|------------|
| [GEOG 868 - Spatial Database Management](https://www.e-education.psu.edu/spatialdb/node/1776)                                           | Medium | PostgreSQL / PostGIS      |
| [Boundless - Intro to PostGIS](https://web.archive.org/web/20170913113658/http://workshops.boundlessgeo.com/postgis-intro/welcome.html) | Medium | PostgreSQL / PostGIS      |
| [CS145: Data Management and Data Systems](https://cs145-fa18.github.io/course_info.html)                                                | Hard      | Google BigQuery       |

</center>

##### Reading (Optional)
- [GeoAlchemy Documentation](https://geoalchemy-2.readthedocs.io/en/latest/)

## Version Control
Learn how to manage projects using version control.

<center>

| Resource (Choose one)                                      | Difficulty | Software   |
|------------------------------------------------------------|------------|------------|
| [Git Documentation](https://git-scm.com/doc)           | Medium     | Git        |
| [Git Offical Resources](https://try.github.io/)                | Medium     | Git        |
| [Git Tutorial by Atlassian](https://www.atlassian.com/git) | Medium     | Git        |

</center>

## ETL
Learn how to extract, transform, and load data.

<center>
  
| Courses                                                                                            | Difficulty                             | Skill Taught  |
|----------------------------------------------------------------------------------------------------|-------------------------------------------|------------|
| [Dataquest Data Engineer Path](https://www.dataquest.io/path/data-engineer) ($24.50 - $50 / month) | Hard | Database Optimizing, ETL, Task Management       |
| [FME Workbench Tutorials](https://knowledge.safe.com/page/tutorials)                               | Medium                          | FME, Spatial ETL      |

</center>

##### Additional Resources
- [Petl Documentation](https://petl.readthedocs.io/en/stable/)
- [Geopetl](https://github.com/rbrtmrtn/geopetl)
- [Using Python Script for Data ETL](https://codeburst.io/using-python-script-for-data-etl-53138c567906)
- [A Beginner's Guide to Data Engineering](https://medium.com/@rchang/a-beginners-guide-to-data-engineering-part-i-4227c5c457d7)

##### Reading (optional)
- [Airflow Documentation](https://airflow.apache.org/)
- [Luigi Documentation](https://luigi.readthedocs.io/en/stable/)

## Web Development Fundamentals
Learn the basics of web development. It's very important to do this before trying to jump into web GIS.

<center>

| Courses (Choose one)                                                                                                            | Difficulty                             | Languages |
|---------------------------------------------------------------------------------------------------------------------------------|---------------------------------------|------------|
| [CS50: Web Programming with Python and JavaScript](https://www.edx.org/course/cs50s-web-programming-with-python-and-javascript) |  Medium     | Python, HTML, CSS, Javascript, SQL        |
| [Colt Steele's Web Developer Bootcamp](https://www.udemy.com/the-web-developer-bootcamp/) ($10, search for coupon)                                      | Medium     | Node.js, HTML, CSS, Javascript, NoSQL     |
| [The Odin Project](https://www.theodinproject.com/)                                                                             | Medium     | Ruby, HTML, CSS, Javascript               |

</center>

##### Recommended Additional Course
- [Colt Steele's Advanced Web Developer Bootcamp](https://www.udemy.com/the-advanced-web-developer-bootcamp/) ($10, search for coupon)

## Web GIS
Learn how to add maps to your web applications.

<center>

| Courses (Do both)                                                                                                        | Difficulty                        | Languages / Frameworks  |
|--------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|--------------------------------------------------|
| [GEOG 863 - Web Application Development for Geospatial Professionals](https://www.e-education.psu.edu/geog863/node/1776) | Easy                                           | HTML, CSS, Javascript, ArcGIS Javascript API    |
| [GEOG 585: Open Web Mapping](https://www.e-education.psu.edu/geog585/node/508)                                           | Medium                                        | QGIS, GDAL, OGR, GeoServer, TileMill, Leaflet    |

</center>
  
##### Recommended Additional Course
- [GEOG 865: Cloud and Server GIS](https://www.e-education.psu.edu/geog865/node/25) - Requires an ArcGIS Enterprise Account and an active credit card to register for AWS free tier.

##### Additional Tutorials
- [Offical Leaflet Tutorial](https://leafletjs.com/examples.html)
- [MapTime Boston Leaflet Tutorial](https://maptimeboston.github.io/leaflet-intro/)
- [MIT Leaflet Workshop](http://duspviz.mit.edu/web-map-workshop/leaflet-js/)
- [MIT Leaflet with PostGIS, NodeJS, and Express Workshop](http://duspviz.mit.edu/web-map-workshop/leaflet_nodejs_postgis/)

##### Reading (Required)
- [ArcGIS REST API Documentation](https://developers.arcgis.com/documentation/core-concepts/rest-api/)
- [ArcGIS: Publishing a map service](http://enterprise.arcgis.com/en/server/latest/get-started/windows/tutorial-publishing-a-map-service.htm)
- [Python - Update Hosted Feature Service](https://github.com/arcpy/update-hosted-feature-service)

## Front End Libraries
Learn how to make modern web applications using front end libraries.

<center>

| Courses (Choose one)                                                                                                                    | Difficulty | Framework / Library |
|-----------------------------------------------------------------------------------------------------------------------------------------|---------------------|------------|
| [Tyler Mcginnis: Free Online React BootCamp](https://tylermcginnis.com/free-react-bootcamp/)                                            | Medium               | React     |
| [Maximilian Schwarzmüller: Angular 7 (formerly Angular 2) - The Complete Guide](https://www.udemy.com/the-complete-guide-to-angular-2/) ($10, search for coupon) | Hard             | Angular       |
| [Maximilian Schwarzmüller: Vue JS 2 - The Complete Guide](https://www.udemy.com/vuejs-2-the-complete-guide/) ($10, search for coupon)                           | Easy                 | Vue       |

</center>

Front end development is such a broad topic that I'm just going to link to the brilliant frontend section of the [2018 Web Developer Roadmap](https://codeburst.io/the-2018-web-developer-roadmap-826b1b806e8d). You will have picked up most of these skills already by now but getting comfortable with package managers, build tools, state management, CSS preprocessors, and front end testing will put you at a great place for front end development.

## Backend Web Development
Learn how to serve data to a client with a backend server. Almost all of the backend GIS development job postings I've seen require .Net Core (C#). I've seen a few GIS projects using Flask, Django (Python) and Java, but C# definitely seems to be the dominant force here.

Backend development is such a broad topic that I'm just going to link to the brilliant backend section of the [2018 Web Developer Roadmap](https://codeburst.io/the-2018-web-developer-roadmap-826b1b806e8d). 

##### Additional Tutorials
- [GeoDjango Tutorial](https://docs.djangoproject.com/en/2.1/ref/contrib/gis/tutorial/) (Python)
- [Make a Location-Based Web App With Django and GeoDjango](https://realpython.com/location-based-app-with-geodjango-tutorial/) (Python)
- [Geospatial for Java](http://docs.geotools.org/stable/tutorials/) (Java)
- [Hibernate Spatial](http://www.hibernatespatial.org/documentation/02-Tutorial/01-tutorial4/) (Java)
- [Proj4J Tutorial](https://trac.osgeo.org/proj4j/) (Java)
- [JTS Topology Suite](http://www.tsusiatsoftware.net/jts/main.html) (Java)
