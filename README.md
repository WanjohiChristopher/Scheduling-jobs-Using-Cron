# Scheduling-jobs-Using-Cron


Cron jobs help us automate our routine tasks, whether they're hourly, daily, monthly, or yearly.

Whats cron,crond? 

cron is a service that runs jobs.

crond interprets 'crontab files and submits jobs to cron.

crontab is a table of jobs and schedule data.
it invokes text editor to edit a crontab file.

This link show how to automatically write the schedules and know when they are executed [Crontabguru](https://crontab.guru/)

This ‘m h dom mon dow command’ is the cron job syntax
  (minute,hour,dayof month,month,dayof week)
example 
```
30 15 * * 0 date >> migrate.txt
```
![carbon (5)](https://user-images.githubusercontent.com/55980747/139671091-fdd08afb-17ef-4f68-90c8-1f1d6c709b13.png)


Use CTR X to exit editor
Enter Y to save changes.

# Example of scheduling jobs

#### Checking cron service
![Screenshot from 2021-11-23 10-59-26](https://user-images.githubusercontent.com/55980747/142988381-b8f95793-4424-4049-81e4-8564143ca4b1.png)



![Screenshot from 2021-11-23 10-54-16](https://user-images.githubusercontent.com/55980747/142988020-dd379c30-061c-4f19-8ee2-f30abd3eb14f.png)

Keep Building stuff!

[Bestexplained](https://www.freecodecamp.org/news/cron-jobs-in-linux/)

