# LoginLogger
Small Python script that logs every login session on Windows

***HOW TO USE***

1. Download LoginLogger file
2. Unzip it in whatever folder you want
3. Run login_logger.bat batch file to enable script to work
4. log.txt is a log file which will be on the same location where .exe is and is used to see every log session on current user. It will appear after executing the script for the first time

***FAQ***

**Q**: Script isn't executing\
**A**: Problem is commonly caused by batch script not creating automated task. To check, go into Task Scheduler and find LoginLogger task, if it isn't on the list, that means that batch didn't create the task succesfully. The solution in most cases is that you need to run batch as an administrator. It should automatically do that by popping up UAC (User Account Control) window, but if it doesn't just right click on login_logger.bat and run it as administrator

**Q**: I'm getting SmartScreen warning, is the batch file safe to use?\
**A**: File is totally safe, you can check the code for yourself on GitHub. If you get a Smartscreen pop up, allow file to execute

***LOG FILE CONTENTS EXAMPLE***

Logged in: 09-09-2023 20:03:04\
Logged in: 10-09-2023 14:37:16
