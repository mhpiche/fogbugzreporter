This simple application written in the Groovy language allows users to connect to [FogBugz](http://www.fogcreek.com/FogBugz/) servers ([FogBugz On Demand](http://www.fogcreek.com/FogBugz/IntrotoOnDemand.html) or server version 6.0+) and produce simple timesheet reports.  For example, you can produce a report of how many hours you logged last week on cases matching a particular filter.

To run the app, just download the main zip file, unzip it to a folder and double click on the JAR file to launch it. If that doesn't work, go to the extracted directory on the command line and type
`java -jar FogBugzReport.jar`

Note: the code is still really raw and has no error checking, so don't expect very robust behavior.  It also requires an installation of Java 5 or above, which you can download from Sun by clicking the download link for the Java Runtime Environment at http://java.sun.com/javase/downloads/index.jsp
