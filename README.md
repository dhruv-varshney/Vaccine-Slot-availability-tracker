# CoWIN vaccination slot availability using Python

Script to check the available slots for Covid-19 Vaccination Centers from CoWIN API in India. This CANNOT book slots automatically. The Indian Government had blocked the API for crawlers, but we are good to go.

The number of severe acute respiratory syndrome coronavirus 2 infected patients keeps rising in most of the countries despite the pandemic precaution measures. The current antiviral and anti-inflammatory therapeutic approaches are only supportive, have limited efficiency, and the prevention in reducing the transmission of virus is the best hope for public health. It is presumed that an effective vaccination against coronavirus 2 infection could
mobilize the innate and adaptive immune responses and provide a protection against severeforms of coronavirus disease 2019 (COVID-19) disease. A step towards this, tracking available slots for Covid-19 Vaccination Centres in India on the CoWIN website can be abit strenuous. In this work have created a Python Streamlit based web application that helps us to check the available slots for Covid-19 vaccination centres from CoWIN API in India. But in the CoWIN API we have to register first and then enter the mobile number for registration 



The [CoWin API](https://apisetu.gov.in/public/marketplace/api/cowin) currently states : "Further, these APIs are subject to a rate limit of 100 API calls per 5 minutes per IP". I tried deploying the Web Application but the API is blocking the request. You can easily run the web application on your machine by following the steps mentioned below.
&nbsp;


Run `streamlit run app.py` on your command prompt or terminal
First it will adk your email id then the program will run .
After execution is successful  you will get a link 
Paste that link in the web browser
