Please find my installation instruction for leshan server:

In the beginning of the class, we set up a leshan server and client on raspberry pi. Firstly I forgot my password of dietpi while trying to login into dietpi. After many attempts I logged in and changed the password of dietpi. Later I installed the following development software in the dietpi terminal:
Git : Clone and manage Git repositories locally. Able to check the version through git --version.
Java JDK : OpenJDK Development Kit. Able to check the version through java –version.
Java JRE : OpenJDK Runtime Environment
Node.js : JavaScript runtime environment.
Installation of maven in raspberry pi
In the dietpi directory, created a folder and reached till the folder. Downloaded the latest maven using wget. Unpacked the tarball, later set the environment variables to add maven to the paths. I made sure the add path is displayed in ~/.bashrc file and tested the maven installation.
Similarly in the same way I installed the JAVA_HOME to the ~/.bashrc file and tested the java installation. Later I cloned the leshan repo using git clone command. I builded the leshan using mvn clean install which took more than half an hour for me.
Later I tested the leshan server using java command and connected to leshan server using diet pi ip address where I can be able to see the dietpi registered as client. I have closed the session by using ctrl+c.

During installation I got a lot of errors during mvn clean and I need to set up the path for java and maven path in ~/.bashrc file later the errors were resolved.

Please find the below Screenshots after installationin leshan server and als find the build success image:

![image](LESHAN_server.png)

![image](BUILD_SUCCEESS.png)
