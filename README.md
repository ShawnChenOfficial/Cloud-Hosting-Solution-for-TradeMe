# Cloud Hosting Solution for TradeMe

This is a project for Cloud Computing paper while author was studying in 2nd year of Bachelor of Information Technology.
The repository contains 3 diagrams and a full documentation.

The project requires to design cloud solutions based on 3 levels of business scale for the TradeMe company as the background, And the cloud hosting techniques are across from IaaS(infrastructure), LaaS(load balancer as a server) to k8s(Kubernetes).

###### Hint: all requirement are not real as all given by tutor.

# Scenario 1:

For the purposes of this scenario we will pretend that Trademe the person to person market platform is launching for the first time in the present day. The founder Shane Gordan has come to your team with the application and asked you to assist in designing a cloud delivery solution to get the application live and available on the internet.
The components of the application at launch are:
	Application Components: 	Business Logic
					Web Front End
					SQL Database
					Bulk Email capability
					Static Files (images, JavaScript, CSS)
Application Function/Details: Provides a platform to connect buyers and sellers of goods, Provides the functionality to auction off good to the highest bidder.

# Scenario 2:
It is 6 years on and TradeMe is a huge success now having sections for listing jobs, properties and motor vehicles. This has however surpassed the capabilities of the start-up cloud delivery design. Trademe is interested in being able to cost effectively scale to handle this huge increase in demand.

New requirements from TradeMe
-	Solution must be able to handle 1 billion requests per month at an average of 1Mb per request
-	Solution should be able respond to the current level of demand and provide cost savings by scaling down in times of lower demand
-	Must have the ability to handle individual datacentre failure
-	User Profiles will now be stored in a MongoDB NoSQL document database, the transactions will remain on an SQL database
-	Trademe is also looking to minimize the ITS maintenance burden of the application delivery platform.
-	TradeMe’s systems engineer has since left the company and TradeMe is looking to outsource the role to an MSP. As such they would like any solution presented to require as little systems engineering/administration as possible so that they do not have to contact their new MSP.

# Scenario 3:

Two more years have passed, TradeMe is happy with the cloud solution you have designed, and it is responding well to the increase in demand. TradeMe is now looking to make some changes and add some features to their existing platform.

New Requirements from TradeMe
-	TradeMe is looking to provide businesses with the option to use their platform as a mechanism to sell to customers, they need a convenient way for the staff at these companies to sign onto the TradeMe platform.
-	TradeMe is focusing on mobile first clients this will mean an API end point for the various mobile apps which will run alongside the existing we frontend.
-	With the mobile first clients TradeMe has encountered an issue with image processing and storage as every picture uploaded for an auction the imaged needs to be resized into multiple copies for the various mobile screen sizes. Doing this efficiently within the existing application has proved a challenge.
-	Finally, Trademe will be rearchitecting their platform to one that uses micro services, so the monolithic application servers are no longer required. This will entail re architecting the way in which the application layer of the application is delivered.

