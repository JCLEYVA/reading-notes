## Class 13 Reading notes

**1.Why would a developer use local storage for a web application?**
Local storage is on the server and it is used to restore data in its recent state after closure of the application or website. This is why you get a cookie prompt every time you to enter a new webpage.

**2.What information should not be stored in local storage?**
Any type of PII or sensitive information that can be accessed by a third party.


**3.Local storage can store what type of data? How would you convert it to that type before storing?**
json.stringify methods converts objects into a string JSON