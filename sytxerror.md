# what is sytxerror

sytxerror is a new collaboration platform for IT, aim is to meet new people, share the knowladge and provide services for everyone for free. it also serves as a platform for job posting.
the application will be built within MERN(Mongo, express,react, and Nodejs) and will have a frontend and a backend.

## Core functions

* everyuser can create a profile
* everyuser can search for others using keywords(profission or location)
* everyuser can post in the knowledge base
* everyuser can post in the market place.
* everyuser can post a job posting or browse available jobs

## nice to have

* a live chat function
* code testing enviroment (like the one in stackoverflow)
* more to come

## Models

### a user model which containes

* userhandle (username) required/unique/ min:4 max:20 string
* an email valid email address(need to be verified) / required/unique string
* a password required/min:10 char, no upperlimit ??? must confirm stringto the following: upper and lower case chars, numbers and spicial ASCII cahrs.
* a type (person, company and an admin) required string
* profile picture (default or upload to cloudinary)

* jobtitle not required string
* company not required string
* location not required string

* knowledge base
* jobs
* services

### knowledgebase Model

* category software, hardware or networking
* a title required min 10 char no upperlimit string
* posted by
* a discription required string
* URL to the documentation page not required string

### job model

* Title string|required|min: 3
* company string| required | min: 3
* location string| required
* posting date
* starting date
* job URL
* posted by

### a service model

* Name
* type free or paid
* category software/hardware/networking
* posted by
* discription
* post date
* status (open, close)
* location
