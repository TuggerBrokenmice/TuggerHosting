# Insurgency Server Manager
A utility to handle start, stop, and restart of the insurgency server instance.  This current version will need some work before it can be installed to a startup script directory such as /etc/init.d/, but it wouldn't be difficult to accomplish depending on how you installed the insurgency server.

## Installation
Copy all files to the root directory of your insurgency installation and make sure ```insserv.sh``` is executable with ```chmod +x insserv.sh```


Edit [CMDLineOptions](/ServerManager/CMDLineOptions) to meet your needs before running

## Get Started

run

```./insserv.sh stop```

from your insurgency install directory
