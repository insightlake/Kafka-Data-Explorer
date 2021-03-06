
<img style="width:100%;" src="images/dataexplorer.png">

What is InsightLake Kafka Data Explorer?
-----------

InsightLake Kafka Data Explorer solution is part of InsightLake Data Platform. It provides an intuitive UI and allows users to connect to Kafka and explore the data easily.

Users can explore the realtime data securely. All the data access is logged.

<img style="width:100%;" src="images/login.png">

<img style="width:100%;" src="images/explore.png">

<img style="width:100%;" src="images/schema.png">

<img style="width:100%;" src="images/realtime-graph.png">

To learn more, check out [http://www.insightlake.com/kafka-explorer.html](http://www.insightlake.com/kafka-explorer.html) 

Installation
------
* Download or clone the repository. 
* Run bin/insightlake command.
* Open browser with URL as http://localhost:8080/
* Add sasl user with username client and password client-secret
* By default H2 database is used, you can change the database details in jdbc.properties file

Installation using docker 
------
* Download or clone the repository. 
* Change kafka configuration in /lib h2.properties file
* cd /docker
* Run `docker-compose -f docker-compose.yaml up --build`
* Open browser with URL as http://localhost:8080/

License
------
InsightLake Kafka Data Explorer is closed source but distributed to be used freely. Please contact contact@insightlake.com for details.

Getting Help
----------

You can get help easily :
Community - Google Groups
Slack Channel
Twitter
Facebook
Email: contact@insightlake.com


