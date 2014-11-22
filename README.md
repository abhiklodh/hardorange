HardOrange
===========

#Node.JS based chat App

###Live Demo: http://hardorange.herokuapp.com/

##Screenshots:
![Picture](http://openhubcls8e.appspot.com/serve/AMIfv97Zh9vwk6oyoJLoSgmFpgAIqpGfcNY8RKNOVgJDiJ9FOEJaxph_wt5FW586dZffzX0T01G3C1lKzdsiO7bhVrro66b0rWaxUNwz0mqfX5ZTVCCdKcXCBqKC4MnbG_8WRv04kdAYnYc1lt043zo7iZSuVBA0USBbwGOqxHtEoyDv2WSSMZI)

##To run:
- Clone repo
- Run ```npm install```
- Run ```grunt``` to compile JavaScript and CSS Files
- Create a ```config.js``` using ```_config.js``` as a template
- Set desired server port in ```config.js```
- Set ```github secret_key``` (if you want to use the [Github Webhook](https://developer.github.com/webhooks/))
- Run ```node app.js```
 
##To push to Heroku:
- Download my repo(of course!!)
- Run```heroku login```(u mast have heroku toolbelt installed)
- Enter ur credentials(not false ones :P)and a heroku account is necessar, Luke!!
- Run```heroku create appname```(appname replaced with ur site subdomain and identifier)
- Run(finally)```git push heroku master```
- If u want to see if ur app is running without going haywire```heroku logs```

