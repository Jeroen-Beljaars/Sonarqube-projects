## Deploying the server

First start a instance of the windows command prompt. This can be done by going into the windows start menu and typing CMD. The command prompt will show up, and press enter.

In the command prompt screen navigate to the folder you placed you Payara instance.
This can be done by using the cd 'folder' command
After that navigate to the bin folder of Payara.

Run the following command to start the server
.\asadmin start-domain
This can take a while to run.
Afther this is done you should see a admin port that runs the Paraya server.

After this go to the default web browser of the system en type the following address :
http://localhost:4848
This should open the configuration screen of the Payara server.

Goto the applications button and select deploy,


Select the file location of the provided .war file and click OK in the right top corner.

The application will now deploy and will be accessible for the system. To make sure the application runs correctly you can click on the Launch button and select one the the deployment locations.