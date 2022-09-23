
I did the following installation/experiment other than professor asked us to do.

a)	Bootstrap Server:

Firstly we need to login through leshan server as above before starting the process. We need to come out of leshan and login through the dietpi. I have moved to downloaded folder and run the command   wget https://ci.eclipse.org/leshan/job/leshan/lastSuccessfulBuild/artifact/leshan-bsserver-demo.jar and this command java -jar ./leshan-bsserver-demo.jar.

Now I start the leshan server by moving cd ~/projects/leshan and run the following java command  java -jar leshan-bsserver-demo/target/leshan-bsserver-demo-*-SNAPSHOT-jar-with-dependencies.jar.

Now we can see the bootstrap client in the leshan server. We need to create add the client configuration and enter the details of the dietpi with the server or we can skip the configuration. So the following the screenshots after adding the bootstrap server.

 

B) Interface testing

We Need to login leshan server as above mentioned in the class. Later when I click on dietpi, I can be able to create the objects here. Now we go to command prompt, we can create object by command CREATE OBJECTID as CREATE 3 / CREATE 4. We can able to see the added objects in the leshan server interface as below.

 
We can able to change the data formats as below for the objects created/objects in the leshan server.

 

We can able to change the instances by selecting R,W commands. We can be able to change the values in the devices, temperature, locations.

 

e) Using wire shark to analyze protocols:

I have logged in leshan server as we mentioned in the class before the wire shark start. I have started and opened the wire shark. Click on double click on WIFI and have to analyze the data traveling back and forth on a network. I can able to read the contents of the packet. I have searched for the http and able to locate the transmission content, able to get the response. I can able to analyze the protocols in the wire shark and please find the screenshot below.

 






