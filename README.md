# SSU
A script that enables all frequencies on Wi-Fi cards; by NPG.\
\
License: GNU General Public License version 3 (GPLv3) or any later version.\
Licensor: Tim Olsson.\
Authors: NPG (autumn 2016).\
\
The script file (ssu.sh) is intended to be executed under a UNIX or Linux operating system environment after installation of the "backport-iwlwifi-dkms_9904-0ubuntu3.1_all.deb" driver.\
\
Bash shell instructions: $ sudo dpkg --install backport-iwlwifi-dkms_9904-0ubuntu3.1_all.deb && sudo echo "backport-iwlwifi-dkms hold" | sudo dpkg --set-selections && sudo ./ssu.sh && iw list && iw reg get
