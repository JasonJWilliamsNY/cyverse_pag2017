# Do more with Cloud Computing

## Exercise - Sharing your Atmosphere desktop with another CyVerse user. 

One of the advantages of computing within CyVerse is shared credentials and user profiles on common computing resources. This makes it easy to transfer data, and to enable collaborator access securely. In this exercise, you will share your Atmosphere desktop with another CyVerse user. 

1. Get the username of another CyVerse user and give them your IP address (from the Atmosphere website). 
2. Connect to your Atmosphere instance via VNC. 
3. In your Atmosphere instance, click the **VNC** icon in the upper right-hand corner of the Desktop; this will open a _VNC Server_ window. <br><img src="https://jacksonlab-workshop-2016.readthedocs.io/en/latest/img/atmosphere_7.jpg", style="width:300px;height:150px;">
4. Click the **More** button on the _VNC Server_ window and select _Options..._; A _VNC Server Options_ window will open.<br><img src="https://jacksonlab-workshop-2016.readthedocs.io/en/latest/img/atmosphere_8.jpg", style="width:300px;height:350px;">
5. Select _Users & Permissions_ from the _VNC Server Options_ window, then click on **Add**.; Enter the CyVerse username of the collaborator you wish to share with; the click **OK**<br><img src="https://jacksonlab-workshop-2016.readthedocs.io/en/latest/img/atmosphere_9.jpg", style="width:300px;height:350px;">
6. Make any adjustments to the user permissions, click **Apply**, the click **OK**. Close the _VNC Server_ window. 
7. Your collaborator can now enter the IP address (+“:1”) to their VNC viewer as the server to connect to. They can connect using  their CyVerse username and their user credentials. ## Imaging an Atmosphere instance

Imaging allows you to save a copy of your Atmosphere instance (including data, installed software, etc.). This means that even after your terminate. These instructions give you an overview of the process but you will need to **Read the [Full Documentation](https://wiki.cyverse.org/wiki/display/atmman/Requesting+an+Image+of+an+Instance)**, including which directories will be deleted or overwritten during the process. 

## Working on other Clouds

### Choosing a cloud platform

The most important thing about *The Cloud* is choice - instead of purchasing a physical computer, you can obtain on-demand computing at almost any scale. This power comes with advantages and disadvantages:

**Advantages of Cloud Computing**
* Access large amounts of computing power on demand
* Full administrative rights - install anything
* Use pre-configured images (software already installed)
 

**Disadvantages of Cloud Computing**
* Cloud computing costs money (you must keep track of your costs)
* If you need help, you may not have a local system administrator 
* Images may be poorly documented (you may not be clear on what is installed, or how to use it)

### Cloud platform choices

There are several cloud providers to choose from. Some scientific clouds may either be free or allocate resources competitively. Commercial clouds are can be very powerful, but choice can be overwhelming. We will cover as much as we you need to get through the Data Carpentry lessons, but you will ultimately need to learn things not covered here so see the documentation below:

#### Commercial Clouds

* [Amazon Web Services](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html)
* [Google Cloud](https://cloud.google.com/compute/docs/quickstart)

#### Open Science Clouds
* [Atmosphere](https://pods.iplantcollaborative.org/wiki/display/atmman/Getting+Started)
* [JetStream](http://jetstream-cloud.org/)


## Launching an Cloud Instance (Virtual Machine)


 > **Tip:** Keep in mind, if you are attending a workshop this will have already been done for you!

We will provide instructions for working on the *Amazon* and the *Atmosphere* cloud. Follow the instructions for your platform of choice.


