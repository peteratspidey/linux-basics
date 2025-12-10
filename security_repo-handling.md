# security and repo-handling tools
## ca- certificates
install trusted Certificte-Authority (CA) certificates
```bash
sudo apt install ca-certificates
```
> allows system to securly communicate with the HTTPS websites or repositories, without this secure download of packages fails

## curl
command line tool for downloading files or making HTTP requests
```bash 
sudo apt install curl
```
> use- to download gpg keys , installation of scripts , API data ,essential for installtion of (docker,nginx ,github etc)
`gpg` keys - digital security keys used to verify the authenticity,safety of the software or packages

## GnuPG
provide gnu-privacy guard 
```bash
sudo apt install GnuPG
```
> use to verify digital signature of downloaded packages, ensures authencity of the repo that u hav added

## lsb-release
provide linux distribution information
```bash
sudpo apt install lsb-release
```
> lets script detect the ubuntu version that u are using, required while adding repo entries
