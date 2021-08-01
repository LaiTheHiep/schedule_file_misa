<p><b>Step 1:</b> Create directory 'C:\ScriptService'</p>
<p><b>Step 2:</b> Copy file 'ScheduleDeleteFile.exe' to folder 'C:\ScriptService'</p>
<p><b>Step 3:</b> Open CMD with Administrator</p>
<p><b>Step 4:</b> cd C:\Windows\Microsoft.NET\Framework\v4.0.30319</p>
<p><b>Step 5:</b> run command: InstallUtil.exe C:\ScriptService\ScheduleDeleteFile.exe</p>
<p><b>Step 6:</b> Open Services, find service 'Delete file' and start it</p>
<p><b>Step 7:</b> Open file 'C:\ScriptService\script.config' and edit parameters</p>
<br/>
<p><b>[NOTE]: Detail parameter</b></p>
<p>CountFile = 5 // the number of files that you want to stored</p>
<p>RootFolders = C:\Misa\backup1, C:\Misa\backup1 // list of folders that you want excute</p>
<p>extentions = .mbk, .txt // list of extention file</p>
