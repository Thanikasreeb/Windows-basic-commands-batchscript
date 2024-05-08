# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file Save each script in a file with a .bat extension.Ensure you have 
the necessary permissions to perform the operations.Adapt paths as needed based on your system configuration.

### Step 3:

Execute the necessary commands/batch file for the desired output. 

# WINDOWS COMMANDS:
```
NAME:Thanika sree B
REG.NO:212222100055
```

## Exercise 1: Basic Directory and File Operations

Create a directory named "MyLab" on the desktop.

## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab
![image](https://github.com/Thanikasreeb/Windows-basic-commands-batchscript/assets/119557910/e2aaf98c-9859-4709-961d-f0e263db5742)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory. %userprofile%\Desktop\MyLab
![image](https://github.com/Thanikasreeb/Windows-basic-commands-batchscript/assets/119557910/e68077c4-61ea-460b-990a-50e592954825)
![image](https://github.com/Thanikasreeb/Windows-basic-commands-batchscript/assets/119557910/8127591c-6075-4d91-ac28-6f53d1496e96)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop. %userprofile%\Desktop\MyLab
![image](https://github.com/Thanikasreeb/Windows-basic-commands-batchscript/assets/119557910/e9642171-fcd4-453e-80fd-4851daa09881)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder. mkdir %userprofile%\Desktop\Backup mkdir 
%userprofile%\Desktop\Backup
![image](https://github.com/Thanikasreeb/Windows-basic-commands-batchscript/assets/119557910/6c1d36cb-1c43-4aa2-8110-bb4b9b6efed1)
![image](https://github.com/Thanikasreeb/Windows-basic-commands-batchscript/assets/119557910/2ddadc05-fb11-429e-b52f-f66d04ff1ab7)

## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![image](https://github.com/Thanikasreeb/Windows-basic-commands-batchscript/assets/119557910/8e6ab0e3-526e-41dc-ac1a-6d8381e2a1f5)

## Exercise 2: Advanced Batch Scripting

Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" 
folder to a new folder named "DocBackup" on the desktop. @echo off mkdir %userprofile%\Desktop\DocBackup 
copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully

## OUTPUT

![image](https://github.com/Thanikasreeb/Windows-basic-commands-batchscript/assets/119557910/ae616c66-fdfc-42c7-9fc1-74ae20bf7bf6)

# RESULT:
The commands/batch files are executed successfully.

