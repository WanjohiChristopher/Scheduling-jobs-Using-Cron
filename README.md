# Scheduling-jobs-Using-Cron

Cron jobs help us automate our routine tasks, whether they're hourly, daily, monthly, or yearly.

Whats cron,crond? 

cron is a service that runs jobs.

crond interprets 'crontab files and submits jobs to cron.

crontab is a table of jobs and schedule data.
it invokes text editor to edit a crontab file.

This ‘m h dom mon dow command’ is the cron job syntax
  (minute,hour,dayof month,month,dayof week)
example 
```
30 15 * * 0 date >> migrate.txt
```
![carbon (5)](https://user-images.githubusercontent.com/55980747/139671091-fdd08afb-17ef-4f68-90c8-1f1d6c709b13.png)


Use CTR X to exit editor
Enter Y to save changes.
