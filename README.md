# Mission-to-Mars

## Overview

This repository holds a flask app that, via python web scraping routines, scrape data from Nasa news and image sites, store them in a Mongo database and can be retrieved visually with a styling html.

### WARNINGS
    1.  Python 3.0 or higher required for app.py application
    2.  Flask installation required for viewing
    3.  Mongo Database installation required
    4.  *redplanetscience.com* - does not allows respond to web scrapping app, you may see *"Failed Handshake"* warnings; however, application will respon and update after a few tries. 

### Resources

    1. **Python 3.0** - Pandas, Jupyter Notebook
    2. **Flask** - PyMongo
    3. **Mongo** - PyMongo
    4. **HTML**

### Software Outputs

    1. ***app.py***   
        a. Python Application that utilizes PyMongo access Mongo Database,
        b. Calls scaping.py to execute python **scraping.py** application, and
        c. Utilizes index.html for final site styling
    2. ***scraping.py*** - web scrapping code that pulls news, images and facts from:
        a. **https://redplanetscience.com/** - NASA news related to mars exploration.
        b. **https://spaceimages-mars.com** - NASA site for latest Mars surface photos.
        c. **https://galaxyfacts-mars.com** - comparison table for Earth and Mars Facts
        d. **https://marshemispheres.com/** - High resolution images of Mars Hemispheres.
    3. ***Templates/index.html*** - styling templaate for flask generated web view.

### Running Instructions:

    1. Clone respoitory to personal directory.
    2. Using command prompt, navigate to cloned folder and enter "Python app.py"
    3. Grab resulting http://127.0.0.1:5000 site and past in broweser window.
    4. Hit Web Scraping button to refresh nad search for new material.  