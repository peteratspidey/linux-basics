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
