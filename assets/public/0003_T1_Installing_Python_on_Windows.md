# Installing Python on Windows
> - [meta] Code: T1
> - [meta] Learning Objective: LO1
> - [meta] CSTA Standard: CPP.L2-05
> - [meta] Tag-Type: Text
> - [meta] Tag-Subject: Tutorial, Install, Python
> - [meta] Tag-Device: Windows

---
Source: [University of California, Irvine](https://www.ics.uci.edu/~pattis/common/handouts/pythoneclipsejava/python.html)

You may want to print these instructions before proceeding, so that you can refer to them while downloading and installing Python. Or, just keep this document in your browser. You should read each step completely before performing the action that it describes.

This document shows downloading and installing Python 3.4.3 on Windows 7 in Summer 2015. You should download and install the latest version of Python.

* * *

## Python: Version 3.4.3

The Python download requires about 24 Mb of disk space; keep it on your machine, in case you need to re-install Python. When installed, Python requires about an additional 50 Mb of disk space.

### Downloading

2.  Click [Python Download](https://www.python.org/downloads/).

    The following page will appear in your browser.

    ![](images/01/installing_windows/pythondownloadpage.jpg)

3.  Click the **Download Python 3.4.3** button.

    The file named **python-3.4.3.msi** should start downloading into your standard download folder. This file is about 24 Mb so it might take a while to download fully if you are on a slow internet connection (it took me about 10 seconds over a cable modem).

    The file should appear as

    ![](images/01/installing_windows/msifile.jpg)

4.  Move this file to a more permanent location, so that you can install Python (and reinstall it later, if necessary).
5.  Start the **Installing** instructions directly below.

* * *

### Installing

1.  Double-click the icon labeling the file **python-3.4.3.msi**.

    An **Open File - Security Warning** pop-up window will appear.

    ![](images/01/installing_windows/openfilesecuritywarning.jpg)

2.  Click **Run**.

    A **Python 3.4.3 Setup** pop-up window will appear.

    ![](images/01/installing_windows/pythonsetup.jpg)

    Ensure that the **Install for all users** radio button is pressed.

3.  Click **Next >** button.

    A new **Python 3.4.3 Setup** pop-up window will appear (**Select Destination Directory**).

    ![](images/01/installing_windows/pythonsetup2.jpg)

    ![](images/01/installing_windows/pythonsetup2a.jpg)

    Click the **Yes** button to use the newest installation.

    The default directory will appear in the bottom as **C:\Python34\** and unless you have a good reason to use another directory, use this one.

4.  Click the **Next >** button.

    A new **Python 3.4.3 Setup** pop-up window will appear (**Customize Python 3.4.3**).

    ![](images/01/installing_windows/pythonsetup3.jpg)

    Use the default customization, which selects the Python Interpreter and all its libraries (about 42 Mb).

5.  Click the **Next >** button.

    In a few seconds a pop-up window titled **User Account Control** will appear, posing the question **Do you want the following program to install software on this computer?**

    ![](images/01/installing_windows/useraccountcontrol.jpg)

6.  Click the **Yes** button.

    A new **Python 3.4.3 Setup** pop-up window will appear (**Install Python 3.4.3**).

    ![](images/01/installing_windows/pythonsetup4.jpg)

    During installation, it will show the various operations it is performing and a progress bar for each one.

    ![](images/01/installing_windows/cmd.jpg)

    Eventually a new **Python 3.4.3 Setup** pop-up window will appear (**Complete the Python 3.4.3 Installer**).

    ![](images/01/installing_windows/pythonsetup5.jpg)

7.  Click the **Finish** button.

Python should now be installed. To try to verify installation, navigate to the directory **C:\Python34** (or to whatever directory on which you installed Python) double-click the icon/file **python.exe**. The following pop-up window will appear.

![](images/01/installing_windows/pythonrunning.jpg)

A pop-up window with the title **C:\Python34\python.exe** appears, and inside the window on the first line is the text **Python 3.4.3 ...** (notice that it should say 32 bit). Inside the window, at the bottom left, is the prompt **>>>**: type **exit()** to this prompt and press **enter** to terminate Python.

You should keep the file **python-3.4.3.msi** somewhere on your computer in case you need to reinstall Python (not likely necessary).

You may now follow the instructions to download and install Java (if you have not already done so), and then the instruction to download and install the Eclipse IDE (for Python, Java, or both ). Note: you you need to download/install Java even if you are using Eclipse only for Python)


