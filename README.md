# Desktop-Sharing-JAVA-
Desktop sharing allows remote access and remote collaboration on a person's computer desktop through a graphical terminal emulator. 

This project has two files REMOTE SERVER SOURCE and REMOTE CLIENT . 
REMOTE SERVER takes the screenshot of the computer on which its running and sends it to the REMOTE CLIENT.
NOTE:BOTH THE COMPUTER SHOULD BE CONNECTED TO THE SAME WIFI OR ETHERNET HUB.

Using ROBOT class in java , we take the input from the client computer(MOUSE AND KEYBOARD) and send it to the SERVER computer.The CLIENT computer can be ANYWHERE and can control the Server computer remotely.

You can remotely create a file , edit any file , delete any file as well as shutdown any system or look over any kind of file as per the requirement. 

========================
BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following in your CMD:

java -jar "RemoteClient.jar" (FOR CLIENT COMPUTER -> PUT THE REMOTECLIENT FOLDER ON CLIENT'S(WILL RECIEVE DESKTOP IMAGE) COMPUTER AND THEN RUN)


java -jar "RemoteServer.jar" (FOR SERVER COMPUTER -> PUT THE REMOTESERVER FOLDER ON SERVER(WILL SEND THE DESKTOP IMAGE) COMPUTER AND THEN RUN)

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, none of the
classpath elements are copied to the lib folder. In such a case,
you need to copy the classpath elements to the lib folder manually after the build.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.
