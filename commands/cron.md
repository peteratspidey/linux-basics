# automate the task for the linux recurring tasks
ex - update system daily , tailscaled service update

## to check the current cron jobs open 
```bash
crontab -l
```
`-l` - to list out the current cron jobs

## to delete crontab 
```bash
crontab -f
```

# to update entries in the crontab
```bash
crontab -e
```
> it will open a text editor of the current cron jobs - add lines like 
```bash
30 8 * * * /home/peter/A.sh
```
to run a bash file regularly at 8:30 in the morning

# to resolve the pass word authentication 
add the crontab into the sudeors file
check the documentation of how to add sudo rights to any commands using [visudo](
