#Step 1: Create directory 'C:\ScriptService'
#Step 2: Copy file 'ScheduleDeleteFile.exe' to folder 'C:\ScriptService'
#Step 3: Open CMD with Administrator
#Step 4: cd C:\Windows\Microsoft.NET\Framework\v4.0.30319
#Step 5: run command: InstallUtil.exe C:\ScriptService\ScheduleDeleteFile.exe
#Step 6: Open Services, find service 'Delete file' and start it
#Step 7: Open file 'C:\ScriptService\script.config' and edit parameters

#[NOTE]: Detail parameter
#CountFile = 5 // the number of files that you want to stored
#RootFolders = C:\Misa\backup1, C:\Misa\backup1 // list of folders that you want excute
#extentions = .mbk, .txt // list of extention file
