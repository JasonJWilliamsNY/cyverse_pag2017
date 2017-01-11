# Introduction to Atmosphere Cloud Computing

[Atmosphere](http://www.cyverse.org/atmosphere) is one of the most versatile components of the CyVerse CI. Anything that you would normally be able to do with your local laptop/desktop, you can do on a virtual machine in the Atmosphere cloud. The advantage of using Atmosphere is that you can get access to greater resources (currently up to 16 CPU, 128GB RAM machines). Additionally, those resources are co-localized with the CyVerse Data Store so that moving to and from your instance is very easy to do. 

>**Tip:** To use Atmosphere, you must have an email address from an academic/governmental institution and request access to Atmosphere through the user portal.  To request access, login to user.iplantcollaborative.org and check to see if Atmosphere is listed under ‘My Services.’ If it is not, scroll down and click the “Request Access” button next to Atmosphere to complete a request form. 

1.	Login to [Atmosphere](https://atmo.cyverse.org/)

### Connecting to Atmosphere instance via SSH

> **Tip:** Your Instance status must be ‘active’ in order for you to connect. Windows users can download [PuTTY](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html) to connect via the terminal.
2.  Open a terminal (Mac/Linux) and connect `$ ssh your_cyverse_username@cyverse.org`
3. You will be asked to save and RSA key to the list of known hosts, enter ‘yes’
4. When prompted, enter your CyVerse password.<br><img src="https://jacksonlab-workshop-2016.readthedocs.io/en/latest/img/atmosphere_4.jpg", style="width:600px;height:375px;"> 

### Connecting to Atmosphere instance via VNC

Some Atmosphere images also are configures with a desktop interface. This can be accessed using a VNC Viewer. Download VNC Viewer from Real VNC to connect to your instance. 

> **Tip:** When you download VNC viewer, the program will ask for an IP address. This IP address is available from the Atmosphere website; log into Atmosphere and locate the IP address of the instance you wish to connect to. 

1. Locate your Instance IP address (next to your instance name)<br><img src="https://jacksonlab-workshop-2016.readthedocs.io/en/latest/img/atmosphere_6.jpg", style="width:480px;height:100px;">
<img src="https://jacksonlab-workshop-2016.readthedocs.io/en/latest/img/atmosphere_5.jpg", style="width:300px;height:175px;"><br>

### Terminating your Atmosphere instance

When you are finished with your instance, you must terminate. Follow the following steps. 

1. If necessary, sign into Atmosphere: [https://atmo.cyverse.org/](https://atmo.cyverse.org/)
2. Locate your instance (e.g. select 'Projects' and then select the project that contains the instance you will terminate.)
3. Click on the instance name to get to the 'Actions' menu. You may then select the 'Delete' button to terminate the instance.  

    > **Warning:** This will delete any data on this instance, so you must move any data you wish to save off the instance (for example by using iCommands). 
5. After reading the warning and confirming you are ready, click 'Terminate' to terminate the instance. 
