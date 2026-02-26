# add any command for which u dont want to ask for the sudo password each time -> add them into the visudo file 
## open the visudo file 
```bash
sudo visudo
```
> this will open a text file

## add commands in the file 
> go to the end of the file and type the command in this format 
```bash
venom ALL=(ALL) NOPASSWD: /usr/bin/apt, /usr/sbin/reboot, /bin/systemctl
```
> the user here is `venom` and the apt reboot and systemctl command are currently in the sudoers
> save it
