Get started with avnet-Cloudant-Boilerplate
-------------------------------------
This is a boilerplate application for Node.js with Cloudant service.

The sample is a Favorites Organizer application, that allows users to organize and manage their files in different categories, while those files are persisted into the database in the background. This application supports uploading files of different types. In the sample, it clearly demonstrates how to access the database service that binds to the application using cradle node.js API.

1. [Install the cf command-line tool](https://www.ng.bluemix.net/docs/#starters/buildingweb.html#install_cf).
2. [Download the starter application package](https://console-classic-20150514-112902.ng.bluemix.net:443/rest/../rest/apps/79f9869c-2454-4fed-872b-92833eba8bf3/starter-download).
3. Extract the package and 'cd' to it.
4. Connect to Bluemix:

		cf api https://api.ng.bluemix.net

5. Log into Bluemix:

		cf login -u dineshbalajiv.it@gmail.com
		cf target -o dineshbalajiv.it@gmail.com -s avnet_US_Space
		
6. Deploy your app:

		cf push avnet-Cloudant-Boilerplate -c "node app.js" -m 512M

7. Access your app: [avnet-Cloudant-Boilerplate.mybluemix.net](http://avnet-Cloudant-Boilerplate.mybluemix.net)
