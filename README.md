# jsCSWwidget
Repository for development of a javascript script for a pluggable CSW client component to use in web applications.

# Deployment
This project's file structure is organized as a java web application. You can complete the deployment by several steps:<br>
1. Download all the files into a local file directory, for example, which named "jsCSWwidget".<br>
2. Move the jsCSWwidget folder into Tomcat's webapps directory.<br>
3. Start up Tomcat server.<br>
4. Access the demo page by visiting the url http://localhost:8080/jsCSWwidget <br>
5. The source code of default page provide a basic tutorial. 

# Development
- On Windows, run any IDE or text editor as Administrator (right click program, `Run as administrator`) in order to be able to edit files in Tomcat's webapps directory.
- As Administrator (on Windows) run `merge.sh` in `\lib\jsCSWwidget\js` to merge all js files in to one, `usgin.csw.widget.min.js`.

# Configuration
jsCSWwidget provide a xml file for initial configuration. You can edit the lib/jsCSWwidget/conf.xml file for your own environment.  
