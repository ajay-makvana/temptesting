# SVNIT-Team9

#Backend (API creation)

Here I had created API using Flask(Python) for reading data from .JSON file so that it can be Easy to Access and created different Endpoint as requirements

**API USE GUIDELINE**

**API LINK (Heroku Deploy)** : https://api-for-hackathon.herokuapp.com/

**Various Request types**:

**1. TO GET ALL DATA (For Get All data)**

Link : https://api-for-hackathon.herokuapp.com/all-ohlc/

**2. TO GET COMPANY SPECIFIC DATA**

Link : https://api-for-hackathon.herokuapp.com/ohlc/KEY_OF_COMPANY

Eg. https://api-for-hackathon.herokuapp.com/ohlc/AAPL for company with key AAPL

Eg. https://api-for-hackathon.herokuapp.com/ohlc/GOOGL for company with key GOOGL

**3. TO GET COMPANY SPECIFIC DATA IN SPECIFIC DATE RANGE**

Link : https://api-for-hackathon.herokuapp.com/ohlc-datewise/START_DATE-to-END_DATE-KEY_OF_COMPANY

Here START_DATE in YYYY-MM-DD format also same for END_DATE

Eg. https://api-for-hackathon.herokuapp.com/ohlc-datewise/2020-03-03-to-2021-08-24-GOOGL for get all data from date 2020-03-03 to 2021-08-24 for GOOGL company

Eg. https://api-for-hackathon.herokuapp.com/ohlc-datewise/2021-07-05-to-2021-08-01-MS for get all data from date 2021-07-05 to 2021-08-01 for MS company

**4. TO GET RECENT VALUES(MOST RECENT DATA (latest DATE data))**

Link : https://api-for-hackathon.herokuapp.com/ohlc-latest/ 

company's Latest Value(Last DATE data which available (here : 2021-08-25)) 

**For More Reffer :** https://docs.google.com/document/d/1VVw-lv5YQrM0cSeOoXl9H5aM32pbDXO0MLzoWOtIHKc/edit?usp=sharing
