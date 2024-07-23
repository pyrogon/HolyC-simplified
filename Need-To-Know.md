-Any program you write that is written in HolyC is going to be saved in a *.HC file. Save all of your documents that you intend to execute with .HC

-Almost every function starts with a capital, which is unique, HolyC is case sensitive, so when needed, capitalization is required

-To exit program, enter ESC. If you are editing a file, hitting escape saves changes.

-To terminate a program, enter SHIFT+ESC. If you are editing a file, SHIFT+ESCAPE will not apply any changes made during the session.

-When you click on a .HC file, the program will open it's source code by default, not run the application. To run the application, open the file, then hit F5.


## Basic Commands
TempleOS is designed so that directory navigation and file manipulation can be controlled via left and right mouse clicks Most of these commands can be invoked through right click. However, there may be a time where manual command execution is required. Here are the basics.

### 1. View Contents within a folder
Dir;

With this command, you can view files and folders stored in the current location of the shell. To view the contents of a folder, simply include the folders name in quotations.
Dir("Directory-name");

To view the content of the folder behind the current directory
Dir("../");

### 2. Change Directory
Cd;

Change Directory works much like Dir; does, except instead of simply viewing the contents of a folder, we are navigating these folders. To open a folder above you include the folders name in quotations.
Cd("directory-name");

### 3. Deleting a file
Del;

This is pretty straight forward, just simply enter the file or folder you wish to delete in quotations.
Del("file.HC");

### 4. Executing an application
ExeFile2;

If you wish to run an application directly without viewing it's source code, you can use ExeFile2 to immediate execute the program.
ExeFile2("program.HC");

### 5. Include
If a program asks you to include the file before running it, you can perform this by following the below example
#include("program.HC");
