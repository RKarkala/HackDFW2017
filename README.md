# CleanEarth.life

CleanEarth.life allows users to understand how much of an impact they have on the envrionment as well as increasing awareness amongst people.

## Getting Started

These instructions will go over how to get the app up and running

### Prerequisites
* To Install:
	* [Maven](https://maven.apache.org/)
	* Application Server (e.g. [Websphere](http://www-03.ibm.com/software/products/en/appserv-was) or [Tomcat](http://tomcat.apache.org))
* To Make Edits and Compile:
	* [Java JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
    * [Vue.js](https://vuejs.org)

### Set Up

Firebase and PostgreSQL hosting must be setup for full functionality.
* Firebase - Edit the 'config' variable located in 'app\src\static' (See Editing for rebuilding Vue)
* PostgreSQL - Set your DB Url to an environmental variable named 'JDBC_DATABASE_URL'


### Installing

Open up Command Prompt or CMD equivalent

To Clone and Navigate to Directory

```
git clone https://github.com/RKarkala/HackDFW2017.git
cd HackDFW2017
```

To Build WAR File
```
mvn clean install
```

WAR file will be located at '\target\LoginProject-0.0.1-SNAPSHOT.war'  
After WAR file is created, simply run it on whatever application server you use

### Editing
Front End - Vue.<span></span>js must be installed - For more information visit: [Vue.js](https://vuejs.org)
* Before any edits can be made, the following command must be run

```
npm install
```
* After an edit is made in the app folder, the following command must be run
```
npm run build
```
* Copy the content of 'app\dist' to 'WebContent' and rebuild WAR


Back End - Java JDK must be installed, no special instructions


## Technology Used

* [Vue.js](https://vuejs.org) - JavaScript Framework 
* [Maven](https://maven.apache.org/) - Dependency Management
* [Java JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) - Backend
* [Heroku](https://www.heroku.com) - Hosting 



