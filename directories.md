# all the linux directories
## bin
bin is short for `binary` that contains executable files or programs

### types of bin
* /bin - contains essential user commands that are required for basic system operations for all users
  - ex- ls , cp, mv, bash, cat
* /sbin - contains systems binaries mainly for system administration tasks , required root permissions
  - ex- ifconfig, shutdown , mount , fsck
* /usr/bin - contains user commands and applications but for system essentials
  - ex - python3, gcc, curl, vim, git
*  /usr/sbin - contains user commands and applications for system administration not system essentials
  - ex- apache2, sshd,
* /usr/local/bin - contains locally installed scripts
* ~/bin - users personal executables scripts
  - ex- custom CLI tools
* venv/bin - python virtual environment executables
  - ex- python , pip, activate
* /opt/<package>/bin - optional package executables
  - ex- /opt/google/chrome/chrome - chrome browser executables
