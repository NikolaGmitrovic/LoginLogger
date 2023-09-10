# LoginLogger
Small Python script that logs every login session on Windows

***HOW TO USE***

1. Download LoginLogger file
2. Unzip it in whatever folder you want
3. Run login_logger.bat batch file to enable script to work
4. log.txt is a log file which will be on the same location where .exe is and is used to see every log session on current user. It will appear after executing the script for the first time
5. Do not delete any of the files provided (except README.md and log.txt as they aren't crucial), because doing so might break the script, they are quite frankly useful and important

**THANKS FOR VISITING AND ENJOY USING THE SCRIPT!**

***FAQ***

**Q**: Script isn't executing\
**A**: Problem is commonly caused by batch script not creating automated task. To check, go into Task Scheduler and find LoginLogger task, if it isn't on the list, that means that batch didn't create the task succesfully. The solution in most cases is that you need to run batch as an administrator. It should automatically do that by popping up UAC (User Account Control) window, but if it doesn't just right click on login_logger.bat and run it as administrator.

**Q**: Publisher not verified in UAC (User Account Control)
**A**: In UAC you will see that the publisher is unknown, that is because in order to be verified (known) you have to pay for the licence (which I don't want to). Of course there are ways to bypass that, but they aren't particularly legal and I don't want to get into any unnecessary trouble

**Q**: I'm getting SmartScreen warning, is the batch file safe to use?\
**A**: File is totally safe, you can check the code for yourself on GitHub. If you get a Smartscreen pop up, allow the file to execute. From my own testing, SmartScreen will only pop up once (like first time use on that particular computer), and with every next use it shouldn't appear again

**Q**: Script not working anymore after changing its location\
**A**: If you change the location of scripts you need to run login_logger.bat again. When you run it you will give a warning that says that task already exists, but in this stage task is broken and needs to be replaced. Just type "y" and press ENTER and that's it

***LOG FILE CONTENTS EXAMPLE***

Logged in: 09-09-2023 20:03:04\
Logged in: 10-09-2023 14:37:16
