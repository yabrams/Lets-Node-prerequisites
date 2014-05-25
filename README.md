Lets Node - Course Prerequisites
================================

Please complete the following steps before taking the course:

1. Make sure you understand the basics of the Javascript language: **objects**, **prototype**, **functions**, **context** etc.

2. Download and install the current version of NodeJS on your machine:
    * Windows & Mac OS X users can download and use the installer from [here](http://nodejs.org/download/ "Download NodeJS")
    * Linux users can download and use the binaries from [here](http://nodejs.org/download/ "Download NodeJS") OR:
        * Ubuntu users can run the following commands:
         
             ```
             apt-get install python-software-properties
             apt-add-repository ppa:chris-lea/node.js
             apt-get update
             apt-get install nodejs
             ```
        * CentOS/RHEL users can run the following commands:         
         
             ```
             yum -y update
             rpm -Uvh http://download.fedoraproject.org/pub/epel/6/i386/epel-release-6-8.noarch.rpm
             yum install -y npm
             ```

3. Open Terminal/Command Prompt and type:
     
     ```
     node -v
     ```
   Output should be equals to 'v0.10.28'
   
     ```
     npm -v
     ```
   Output should be equals to '1.4.9'
   
4. Make sure you have a **Git** client installed on your machine and that you can easily clone git repositories, if not, install it by:
    * Windows users can download and use the installer from [here](http://msysgit.github.com/ "Download Git")
    * Mac OS X users can download and use the installer from [here](http://sourceforge.net/projects/git-osx-installer/ "Download Git")
    * Ubuntu users can run the following command:
         
         ```
         apt-get install git
         ```
    * CentOS/RHEL users can run the following command:
         
         ```
         yum install git-core
         ```
         
5. Make sure you run the WebServer and the TCPServer examples, Do it by using the following commands:
     
     ```
     git clone https://github.com/itkoren/Lets-Node-prerequisites.git prereq
     cd prereq
     node webserver.js
     ```  
   AND 
   
     ```
     node tcpserver.js
     ```

6. Make sure you have **IntelliJ IDEA** IDE or **WebStorm** IDE, installed on your machine, together with the NodeJS Plugin - Although you are free to use the IDE of your choice, I'll be using one of those IDE during the course, and I am not going to deal with debugging problems on other IDE's during the course

7. **Windows users**: make sure you have **PuTTY** installed on your machine, if not, download and use the installer from [here](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html "Download PuTTY")

8. Make sure you have an active **GitHub** account, which you can log into - we may be using it during the course


#####*If you've completed all the above - You are ready to Node!!!*