Place install script for new apps in _install/. An install script contains the unpacking or apt-get commands and also the configuration.

New apps need an entry in the menu in install.sh

The scripts depends often on backups from personal config files from previous installations and can be compared with meld.

Call the script with sh install.sh it will ask for sudo rights. Meld is dependency and will be checked.
