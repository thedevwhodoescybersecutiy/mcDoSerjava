1. Download and Install Java on Your PC.
As mentioned earlier, if you want to run JAR files on Windows 11, you’ll need to download Java. If you already have it but are a bit unsure, you can find out by running a simple command in the Command Prompt.

Here’s how:

First, press the Windows key from your keyboard and type ‘cmd’ in the Search bar.
Next, click Open from the right pane.
open Command Prompt
When the prompt opens, type this command and hit the Enter key:
java -version
Run JAR Files on Windows 11
In case your computer doesn’t own Java, you’ll get an error stating that Java is not a recognizable command. Then, you’ll have to download the Java Runtime Environment or JRE. To do so, follow the steps below:

Begin by going to the official Java download page.
Then, scroll down to the downloadable files mentioned for Windows. 
Run JAR Files on Windows 11
By default, the latest compatible version of Java will download and install on your PC.


2. Run JAR files on Windows 11 by Double-Click.
As soon as you install Java Runtime Environment, your JAR files will be detected and displayed in Java executable form instantly. That means you’ll only need to double-click on it to run it on your computer.

In case it doesn’t, here’s what you need to do:

Firstly, navigate to the folder where the JAR files are located.
Then, right-click on the file you wish to open.
From the list of options, hover your cursor over Open with and choose Java(TM)  Platform SE binary.
Run JAR Files on Windows 11
If you don’t see it on the list, click on Choose another app.
Next, scroll down to the Java(TM) Platform SE binary and click on it.
Also, check the box for Always use this app to open .jar files, then click OK.
Run JAR Files on Windows 11
3. Create A .bat File.
If you’ve made a custom .jar archive and want to run it on other PCs, then creating a .bat file is the best option for you. BAT or Batch files utilize the Windows Command Prompt to execute a series of line commands that are stored in a plain text file.

Here’s what you need to do to create a .bat file:

To get started, launch File Explorer.
From the options at the top, tap on the three-dots menu icon.
From the drop-down options, choose Options.
File Explorer options
When the Folder Options window opens, click on the View tab.
Under Advanced settings, scroll down to Hide extensions for known file types and uncheck the box next to it.
Hide extensions for known file types
Click OK to save these changes. The file names will now include the file extensions as well.
Now, navigate to the folder where your JAR file is, open a Notepad in the same location and type the following. Remember to replace “yourfilename” with the name of the .jar file.
java -jar yourfilename.jar
Finally, save the file with the .bat extension.
Now, every time you double-click the BAT file, it will take you to the JAR file and run it accordingly. However, if it doesn’t, move to the following method to fix the related issue.


4. Check the Java File Association.
When you create a .bat file that’s associated with a .jar file, you should be able to run it without any difficulty. But if it doesn’t, you need to make sure that the JAR file association is working properly and fix it if needed.

There are two different ways to do the task. If you want to do it through Windows Settings, follow these steps:

To start, press Windows key + i from your keyboard. Alternatively, go to the Start menu and click on the Gear icon. This will launch the Settings window.
Then, go to Apps from the left pane.
From the right pane, choose Default apps.
Default apps Settings on Windows 11
Scroll to the Related settings at the very bottom and click on Change defaults by file types.
Next, click on the Search bar, type ‘jar’ and hit Enter.
Click on the search result that appears below.
Lastly, choose Java under Other options, then click OK.
You can also perform the same task from the .jar file properties. Here’s how:

Firstly, select the .jar file you’d like to open and press Alt + Enter from your keyboard. Or else, right-click on the file and choose Properties.
Under the General tab, click on the Change button next to Opens with.
Run JAR Files on Windows 11
Next, choose Java under Other options and click on OK.
Again, click on OK to save these changes.
After that, all JAR files should open by double-clicking on them. 


5. Use Command Prompt to Run JAR files on Windows 11.
If you failed to run JAR files on Windows 11 using any of the methods above, it’d be a relief to know that Windows Command Prompt can do the job for you, that too, with only a single command.

For that, follow these steps:

Start by going to the folder that contains the JAR file you’d like to open.
Now, click on the Address bar at the top, type ‘cmd’, and then hit the Enter key from your keyboard.
open cmd
Doing so, the Command Prompt will launch. Now, run the following command except change “NAME” with the .jar file name.
java -jar NAME.jar
Your JAR file will successfully run after that.
