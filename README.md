# cron
A nifty cron setup

Copy the 'cron' subdirectory from this repo (which contains runcron) to your home directory, and edit the files as needed for your system.  Read the comments in ```runcron``` to see how to use it.

```cp -r cron ~/```

Files that need to be executable:
- cron/runcron
- cron/<subdir>/XX_<somename>

To initialize your crontab, you can ```crontab crontab.master``` to replace your current crontab with crontab.master, and then ```crontab -e``` to edit for your system.

