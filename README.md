# webapp_deployment_oncloud

![1  diagram](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/0140591e-ea6d-4736-b884-13930f0f9798)

> **Pre-Requisites**

a. Simple Java webapp project.

b. GitHub Account.

c. AWS Account.

d. Jenkins Server (Linux).

e. Tomcat Server (Linux).

f. Maven & Git Installation/Configuration.

> Create one ec2 instance as Jenkins Server with Ubuntu.

![2  Create one Ec2 instance as Jenkins Server with Ubuntu](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/8e7fbb27-c68d-4b1d-ae05-6ae5411ff8de)

> Launch the Instance.

![3  launch the instance named jenkins](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/22b1fb43-fe6d-4959-a567-6ba7211838fb)

> Connect the Instance and run the first command.

![4  Connect it and run the first command](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/bacfcbd1-7932-435c-adec-611bb46c9a67)

> Run the second command to install Java.

![5  run the second command to install Java](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/1c413c40-fab8-4e36-9aed-2768a24f5ede)

> Run this Command to check the Java Installation and version.

![6  run this command to check the java version](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/75345b08-5f5c-4fe8-b16c-39b3c7052457)

> Copy and paste this bash command in theterminal to install jenkins.

![8  Copy and paste this bash command in the terminal to install jenkins](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/44b3d418-eb68-4f4a-a4af-04382e9f4c46)

> Run this command to check Java Installation.

![9  Run this command to check the installation of jenkins](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/98146703-7e8f-4e96-bd98-c84359670bcb)

> Run this command to enable,start and check the status of jenkins.

![10  Run this Command to enable start and check the status of jenkins](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/bf928a6d-0c66-46f4-b47b-08035cece0f4)

> Go to instance and copy the public ip of jenkins server and paste it to the browser.

![11  Go to instance and copy the public ip of jenkins server and paste it to the browser](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/0f469a59-9abb-482b-9053-83d5d4219660)

> Add TCP/IP 8080 in the inbound rule of security group.

![12  add tcp ip 8080 in the inbund rule of the security group](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/0ba17432-6314-4916-8ced-05405ca492a8)

> Jenkins Start page will appear.

![13  after this jenkins start page will appear](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/f62ff41d-6ac4-4eed-a39a-4870dab596b6)

> Run this command to check the password to unlock Jenkins.

![14  to check the password to unlock jenkins run this command](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/ebfd39d6-cf97-4b0b-92ab-88e8ace2d9aa)

> Paste the command to Continue.

![15  Paste this command to continue](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/6b066178-1afb-46f8-a94c-1482c35471a5)

> Click On "Install Suggested Plugins" to continue.

![16  Click on install suggested plugins to continue](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/2d5c453e-98b7-4896-ab0a-64b4a23d4790)

> Create the default username and password as admin admin.

![17  Create username and password as admin admin](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/6bac527a-6edb-4fa4-84ed-99f172f4756c)

> Save and Finish to start.

![18  save and finish and save the url and then click on this start using jenkins](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/e1e6a34b-0063-40c8-b101-5c20e9bcb96a)

> Homepage of Jenkins Appears.

![19  Come to the homepage of jenkins](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/095a9ec3-3eb0-48a1-8f97-86fc02ababd7)

> Go to Manage Jenkins and then go to Tools.

![20  Go to manage Jnekins and then tools](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/6199c8e1-6dfe-4940-a047-935a4431ea67)

> Go To Add Maven select the version name and save.

![21  Goto Add maven select the version and name and save](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/5c9fb5e2-81c1-403f-b343-8e4ced95b43e)

> Creat a free-style Project.

![22  Now go to new name and add a project under freestyle](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/3a556bec-36d4-4ace-9c70-a576dab9d286)

> After saving go to Job Configuration and enter the repository url in source code management.

![23  After savinf go to job configuration and enter the repository url in source code management](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/06e7ba31-2a42-4c2f-9abb-c2218690bbaa)

> Go To build option and select "invoke top-level maven target then select the maven version and goal.

![24  go to buil option and select invoke top-level maven targets then select the maven version and enter goal as shown](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/c0b8cf4f-9dda-4005-9cc0-0345007f32f5)

> Check the Job building it.

![25  Now we will buils the job and check if my job is working fine or not](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/1a02e36a-c683-4f38-ba36-db09776663bc)

> Check the Jobs Success.

![26  it gets success](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/0c46cf20-ca1c-49b7-98bd-b3367c926523)

> Now we have to launch another instance named Tomcat Server.

![27  Now we have to launch an instance name tomcat with ubuntu](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/19fc5f6d-b841-4562-8379-3c4586a44a0c)

> Connect Tomcat through terminal.

![28 Connect tomcat instance with gitbash or any terminal](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/c9b57c2e-6f43-4acd-b69c-eb441dc29b5f)

> Run this command to update.

![29  run this command t0 update](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/80e207ee-6574-4f0c-bf93-8ba5657164dd)

> Go to apache Tomcat official address and copy the link address for tar.gz

![30  go to apache tomcat official address and copy the link address for tar](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/ce015727-80b1-4f05-892d-d0c358ed84d8)

> Run this command to download the tar file.

![30  run this command to download the tar file](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/2fad3b7e-cdc2-4eaa-95ea-63b9677d710a)

> Untar the file with this command.

![31 untar the file withi this command](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/38090e3d-b151-49a3-bebe-28bc37367ff3)

> Go inside the apache tomcat inside the bin directory.

![32  now go inside the apache tomcat and then inside the bin directory](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/60b9d630-520a-4c3b-8cbb-66d529f598c0)

> Before Going further we have to install JAVA.

![33  before moving further we have to install java](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/1a7cef11-30e5-4dc3-a7ff-5d5c2c2a560b)

> Check the JAVA installation.

![34  Check java installation](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/ba6b1f72-e447-41b8-8af1-20f6cab9c986)

> After Java installation, go to apache tomcat directory then inside bin directory.

![35  after java installation, goto apache tomcat directory then inisde bin directory](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/620b9637-cc79-4a3a-b335-7728a62bb745)

> Execute the shutdown and startup bash command to restart the tomcat service.

![36  execute the shutdown and startup bash command consecutively](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/c0fce6e9-a7b8-4c3b-b653-9512a202ad81)

> Now go to browser and paste the public ip in the browser to access the homepage.

![37  now go to browser and paste the public ip of tomcat and open its homepage](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/5d02e27f-61a1-4ffe-88fa-36a4d753c3e2)

> Jenkins and Tomcat are accessed through 8080 port, so to change in Tomcat server we have to edit server.xml  file.

![38  edit server xml file and goto connector port edit 8080 to 8090 and save it](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/f4eae002-2b52-41f0-b4ac-08a3d3840f56)

> After changing the port restart the tomcat service then add this 8090 port to security inbound rule.

![39  after changing the port restart the tomcat service add this 8090 port to security](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/06b02cdd-5810-498c-b796-0774b1cdda33)

> Tomcat started on port 8090.

![40  tomcat started on port 8090](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/194ca662-7230-416c-b4e5-f2fcc2319b90)

> Click on manager app on Tomcat homepage.

![41  now click on manager app on tomcat homepage](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/d648b1b2-37a9-4123-9ef8-0db7f78ddc84)

> This error page will appear so we have to edit context.xml file.

![42  we will find this error page so we have to edit this context xml file](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/31d12a47-ae3a-4824-bc88-f6812db9e5ac)

> Run this Command to find context.xml file.

![43  run this command to find this context xml file](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/0fbccd75-4294-4a29-be4f-6ed522780421)

> We have to edit this file disable the bValue and Class option.

![44  wew have to edit this file and disbale the bvalue and class option](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/53c2c3cc-9a8c-44d6-82f0-2c72899a8389)

> Under Insert mode go to valve classname and disable it as shown in below pic.

![46  now edit the another file as previous one by disbaling the valve classname](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/5468f48f-7de4-4904-bee5-c440b78b31fb)

> Disable the class valvename.

![47  diable the class valve name](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/eaf583e1-e115-403a-9e71-db37715ebb65)

> After modifying these two files we have to restart the tomcat service.

![48  after modifying these two files we have restart the tomcat service again](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/95a637e4-54f8-4986-9ae9-e53921151c2f)

> After restarting the Tomcat service click on manager App it will ask for login credentials.

![49  after restarting the tomcat service we again click on manager app then it wil ask for username and password](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/ed36f46f-d8ba-4a8d-9ab9-6c3a0441fe55)

> Now go to conf directory.

![50  go to conf directory](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/ebd39ef5-13c1-4320-9e5e-668c0aa8fee6)

> Edit the tomcat-users.xml file.

![51  edit the tomcat-user  xml file](https://github.com/howdycloudyarsh/webapp_deployment_oncloud/assets/133496386/67a8bf59-0f4e-4f78-afb5-c84cb97124ef)

> Paste 



























