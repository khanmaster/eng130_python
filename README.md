# Python Installation Instructions
## Pycharm set up

### Elivator's Pitch
- it's an introduction of yourself should include x y z


### What is Agile
-
-
-
-
-

### What is Scrum
-
-




* Installing Python & pip
* Installing Pycharm



## Installing Python & pip

### Windows Installation
Head to [https://www.python.org/downloads/]() and download the latest save the application locally.

You should have an installer saved and at the time fo writing this document the Python version is 3.7.2. When the installer is open you will have the option to install now, ensure you check the 'Add Python <version number> to PATH' as below.

![](../assets/Python_win_installer.png)

This will make Python available to you on the cmd prompt for Windows.

As a final check once installed head to the cmd terminal and type `python` and hit enter which should leave you with the below output:

![](../assets/cmd_python.png)

pip is python's package manager which we will use in the later stages of this python course. pip has been installed as pert of the overall Python installer and will be in place.


### Mac Installation
To install python on a mac, we have to get a little more technical. Start off by heading to [https://www.python.org/downloads/]() as with windows and download Python 3.7.2.

Once the program is downloaded, open it and click through the process until python will be installed on the machine. To test this has worked, open the mac Terminal program and type `python3`. You should be presented with the following:

![](../assets/cmd_python_mac.png)

To escape this prompt, use CTRL + D.

To install pip, the package manager, we need to type the following lines into the terminal: 

```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3 get-pip.py
```

Please note, to use python from the command line on mac we need to use the `python3` command. The command `python` will use an older version of python (2.7) which is less useful and often won't work.

To finally test that you've correctly installed python and pip, the command `pip -V` should return the following: 

```
pip 19.0.3 from /Library/Frameworks/Python.framework/Versions/3.7/lib/python3.7/site-packages/pip (python 3.7)
```

## Pycharm

Pycharm is a very useful Integrated Development Environment (IDE) which will help ensure your code is correctly formatted, methods are used correctly and all the necessary closures are set.

There are many IDE's out there such as Visual Studio Code, Atom and many many more. Pycharm is a free IDE created by JetBrains who run one of the most widely used IDE's globally called IntelliJ. 

Head over to [https://www.jetbrains.com/pycharm/]() and download the latest version for both Windows or Mac. You will need to download the community edition as this is the free open source version.

Once downloaded open up Pycharm and step through the various options, leaving the defaults and clicking through to the next screen when prompted. We recommend installing **Markdown Support** when prompted as this will be helpful later.

Eventually you will be met by the 'Create New Project' so you're set to go!

## The obligatory 'Hello World!'

The 'Hello World!' program is everyone's first program and it also serves to show that the set up is correct. So, let's go for it.

Click on the 'create a project' option on the IDE and when you see the new project screen name it 'Hello_World' and create. You will see that Pycharm is creating a virtual environment. The IDE is doing a lot of the work for you in the background and we will cover more on Python virtual environments later in the course.

At this stage open up the project on the left hand side and it should look as below:

![](../assets/pycharm_hello_world.png)

These are all files related to a Python virtual environment and again we will cover this in a later course, for now we're going to create our own file.

Right click on the 'hello_world' folder select New -> Python File and click, call the file `hello_world`.

You should now have a new empty file called `hello_world.py`.

 In the file type `print("Hello World!")`. Print is a method that allows you to pass it a value of which it will print it our to the command line.
  
Then, right click on the `hello_world.py` file and within the menu options you should see **Run 'hello_world'**. Click this and the program should spin up and print out `Hello World!` to the CMD prompt in the IDE.
 
