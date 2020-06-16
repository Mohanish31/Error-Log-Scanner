# Error-Log-Scanner
Work only in linux server Find error logs " Null pointer" and other critical issues with cron job we can execute on daily basis 


"""
#Creator:Mohanish Pillai 
#Email ID : Mohanish.Pillai2@harman.com
"""

###How to Run the Script###

Steps:

1) Open Putty 
2) Go to Path
3) CMD: python3 python_Log_Scanner.py

**Note : If it gives any error RUN CMD: chmod u+x python_Log_Scanner.py  for making the script excutable then run step 3..
Task performed by utility
1) Scan all the log file.
2) Create a folder, the day when its run.
3) Generate log file in format of text and excel.
4) Logs in excel file are separated by column : make easy to plot pivot or chart.
5) Scan all the file and take only todays date logs and generate an excel file.
6) Sending mail after completion of task.
7) Scheduler the program to run every day at 8 pm through crontab.
8) Code can manually executives by shell.
9) With the little modification it is working for Audiences
10)Property file :  No need of touch the code , changes can be done in property file, only put the property file path in code


Updated Feature
+ Chunking of files
+ 15 days analyised bar chart Total number of logs per day
+ Total error count and critical count in email
