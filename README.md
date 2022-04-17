# Struts-Sample-DWA
Struts2 Dynamic Web Application Sample

# Requirements
1) Download and install latest Java Jdk or if installed configure in Eclipse itself
2) Download Apache Tomcat server version (9/10) or you can download in Eclipse itself
3) Download and install the latest version of Eclipse
4) Download essential lib from https://struts.apache.org/download.cgi

(I have installed Eclipse IDE For Enterprise Java and Web Developers)

# Setup

## Setting up Java EE (Dynamic Web Project with other options) perespective for Eclipse -

1) Click on Help and then click on “Install New Software”.
2) In Work with paste this link: 2022-03 - https://download.eclipse.org/releases/2022-03/ Change the link according to your Eclipse version (2022-03 is version)
3) Scroll down to find “Web, XML, Java EE and OSGI Enterprise Development” option and expand it.
4) Select the following three options under “Web, XML, Java EE and OSGI Enterprise Development”

- Eclipse Java EE Developer Tools
- Eclipse Java Web Developer Tools
- Eclipse Web Developer Tools
- JST Server Adapters & JST Server Adapters Extension (For Apache Tomcat Server)
- Click next,accept terms install, after everything is installed, restart Eclipse. 
- Now you will see on top right "open perespective --> Java EE"

## For Dyamic Web Project

The newer version of Eclipse,generate new project structure that contains a webapp and for me I need WebContent

1) New-->Dynamic Web Project-->give name to your project--->click on next button
2) Remove src\main\java folder
3) And type only src-->click on next button
4) Rename Content directory as WebContent-->select generate web.xml deployment descriptor
5) Finish.

## lib

1) After download the struts lib archive,unzip it and copy the lib
2) Paste and overwrite the lib in WEB-INF/lib

## Apache Tomcat Server

1) Right click on your project-->Targeted Runtimes
2) Add new or select if any version is present

### In Eclipse, in Servers Tab, you will see "Tomcat vX.X Server at localhost" or it may differ, if you set it up correctly.

## Run Project

1) Right click on your Tomcat Server --> Add or Remove
2) Add your "project-name" from Available->Configured side.Finish.
3) Start the server either by right click on Tomcat Server or on play button to stop do the same and stop

## See

On your browser check http://localhost:8080/samp/ , http://localhost:8080/samp/index.action , http://localhost:8080/samp/hello.action
