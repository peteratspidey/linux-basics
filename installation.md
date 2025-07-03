# installation and removal of packages using `dpkg` , `apt` , `snap` 
## install a downloaded .deb file using dpkg 
### download .deb files using curl and wget
#### using wget
```bash
wget <url>
```
#### using curl
```bash
curl -o <url>
```
### install downloaded package
```bash
sudo dpkg -i package_name.deb
```
> `-i` stands for install 
## installing a package using apt package manager
```bash
apt install <package_name>
```
> give the package name u want to install
> ex:- `sudo apt install vlc`

### fix broken dependencies (if any)
```bash
sudo apt --fix-broken install
```

## to install a package using snap 
```bash
sudo snap install <package_name>
```
