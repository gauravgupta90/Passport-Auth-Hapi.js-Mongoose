Hapi-Mongoose-Passport Example
==============================

The purpose of this app is to show a new way to work with Hapi.js, Passport.js, Mongodb, Mongoose, Angular.js.


### Install an app

Run the following command in root directory of an app in command prompt.

###### *Install node packages*

server/ npm install

### Run an app

###### *Run Server*

Run the following command in root directory of an app in command prompt.

server/ node server.js

You can see the port number in command prompt after sucessfull run

You can change the settings in server/config/config.js file

### *API Available*

###### *Register User*

	POST: http://localhost:8080/register

	{
	"email":"someEmail",
	"password":"somepassword",
	"userName":"gauravgupta90"
	}

###### *Login*

	POST: http://localhost:8080/login

	{
	"email":"someEmail",
	"password":"somepassword"
	}

###### *Logout*

	GET:  http://localhost:8080/logout
      

### Other Usefull Link

[Express-Mongoose-Angular] (https://github.com/gauravgupta90/Hapi-Mongoose-Angular-Node.js)

[Token-Based-Auth-With-User-Roles-Hapi-Mongoose-Mongodb-with-email-verification-and-forgot-password] (https://github.com/gauravgupta90/Token-based-Auth-with-user-role-in-Hapi-Mongoose-Mongodb-with-email-verification-and-forgot-password)


