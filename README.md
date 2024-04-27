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

![output1](https://github.com/allenjoveth/Windows-basic-commands-batchscript/assets/139422287/fabc6daf-5c2e-4cb0-b2b0-89fbacb5dc40)



## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab

![output2](https://github.com/allenjoveth/Windows-basic-commands-batchscript/assets/139422287/fd535bd5-f21c-4288-952b-c29738008fb0)





## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab

![output4](https://github.com/allenjoveth/Windows-basic-commands-batchscript/assets/139422287/1a514337-3ebc-43d2-a818-81667bbf9632)



## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![output5](https://github.com/allenjoveth/Windows-basic-commands-batchscript/assets/139422287/04e0a3b1-47e2-4e2c-881a-6898a4154cc2)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents

![output7](https://github.com/allenjoveth/Windows-basic-commands-batchscript/assets/139422287/a9eb17d3-912d-4845-816b-e557b60bf1f9)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!






## OUTPUT

![output8](https://github.com/allenjoveth/Windows-basic-commands-batchscript/assets/139422287/235010b3-bedd-4833-8c10-f5feb6a42f84)



# RESULT:
The commands/batch files are executed successfully.

