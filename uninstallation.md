# uninstallation using terminal 
## check the installation and package manager
### in apt 
```bash
dpkg -l | grep <package_name>
```
### in snap
```bash
snap list | grep <package_name>
```
### in flatpak
```bash
flatpak list | grep <package_name>
```

## using apt 
```bash
sudo apt remove --purge <package_name>
```
```bash
sudo apt autoremove
```

## using snap
```bash
sudo snap remove <package_name>
```

## using flatpak
```bash
flatpak uninstall <package_name>
```

## remove all the installed packages (restore to default packages) using the interactive package name **aptitude**
### install the aptitude 
```bashn files store settings and preferences for how a program be
sudo apt install aptitude
```
### to delete packages and its configuration files
```bash
sudo aptitude purge ~c
```
> `purge` remove packages and their configuration files and the `~c` is used to remove the residual files

### to remove the packages that are automatically installed as dependencies but no longer required
```bash
sudo apt-get autoremove --purge
```
> `autoremove` -identifies ophanages packages and `--purge` remove their configuration files
