# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 
# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.
## COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\MyLab 
![Screenshot 2025-05-25 191740](https://github.com/user-attachments/assets/2a648c37-e816-48a4-8b11-cc60f4b0ed4e)
## COMMAND AND OUTPUT
cd %userprofile%\Desktop\MyLab 
![Screenshot 2025-05-25 191834](https://github.com/user-attachments/assets/245dc39f-1b95-4b52-ac1a-07cb05430aff)
type nul > MyFile.txt 
![Screenshot 2025-05-25 191904](https://github.com/user-attachments/assets/f8ad646f-56ce-4bf4-bfba-15624cfd17cf)
List the contents of the "MyLab" directory.
## COMMAND AND OUTPUT
dir %userprofile%\Desktop\MyLab 
![Screenshot 2025-05-25 191557](https://github.com/user-attachments/assets/67b23934-2874-4a61-80e6-32ba4bcb6f8f)
Copy "MyFile.txt" to a new folder named "Backup" on the desktop
## COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\Backup 
![Screenshot 2025-05-25 191414](https://github.com/user-attachments/assets/922713ce-707d-43a8-b661-f4e428b6da72)
copy MyFile.txt %userprofile%\Desktop\Backup 
![Screenshot 2025-05-25 191451](https://github.com/user-attachments/assets/ca354579-0c10-473b-ab57-1c864f61fcd1)
Move the "MyLab" directory to the "Documents" folder.

## COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\Documents
![Screenshot 2025-05-25 190926](https://github.com/user-attachments/assets/915e2366-505c-4279-8233-8e9b531ac996)
## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```

## OUTPUT
![Screenshot 2025-05-25 190656](https://github.com/user-attachments/assets/83b7a5b6-7b86-47cc-880f-2905b94967fb)

# RESULT:
The commands/batch files are executed successfully.

