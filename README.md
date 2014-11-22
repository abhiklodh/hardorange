HardOrange
===========

#Node.JS based chat App

###Live Demo: http://hardorange.herokuapp.com/

##Screenshots:


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

