image_project
=============

*IEPUG Group Learning Project*


To install the module dependecies use the following (from within your virtual environment!):
```
pip install requests
pip install beautifulsoup4
pip install html5lib
pip install exifread
pip install sqlalchemy
```


Additional Info
---------------
In general, the overall idea of this sample project is to scrape a bunch of images off of flickr from something like [this search](https://www.flickr.com/search/?q=california&cm=apple%2Fiphone_5s), extract some GPS EXIF info from the images, save the images to local storage, and insert some meta data into an sqlite database using SQLAlchemy.

Additional steps will be to do some GIS tasks with the GPS info we saved, and then create a web app using flask.  After that we can put the web service in the cloud.
