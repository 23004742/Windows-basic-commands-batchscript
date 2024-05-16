# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
type nul > MyFile.txt
## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
dir %userprofile%\Desktop\MyLab

## COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\Backup

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

mkdir %userprofile%\Desktop\Documents
move MyLab Documents





## OUTPUT

![image](https://github.com/23004742/Windows-basic-commands-batchscript/assets/150319318/56b5c9e7-d9f9-4ce9-8773-b5bb06d85079)




# RESULT:
The commands/batch files are executed successfully.

