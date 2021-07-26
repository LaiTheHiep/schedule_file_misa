<p>Step 1: Create directory 'C:\ScriptService'</p>
<p>Step 2: Copy file 'ScheduleDeleteFile.exe' to folder 'C:\ScriptService'</p>
<p>Step 3: Open CMD with Administrator</p>
<p>Step 4: cd C:\Windows\Microsoft.NET\Framework\v4.0.30319</p>
<p>Step 5: run command: InstallUtil.exe C:\ScriptService\ScheduleDeleteFile.exe</p>
<p>Step 6: Open Services, find service 'Delete file' and start it</p>
<p>Step 7: Open file 'C:\ScriptService\script.config' and edit parameters</p>
<br/>
<p>[NOTE]: Detail parameter</p>
<p>CountFile = 5 // the number of files that you want to stored</p>
<p>RootFolders = C:\Misa\backup1, C:\Misa\backup1 // list of folders that you want excute</p>
<p>extentions = .mbk, .txt // list of extention file</p>
