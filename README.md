# ONOSInstallHelper

This is a automatic installation script for install ONOS on Ubuntu 12.04+.

To make installation easiest. This helper script which should get all dependencies and download, build, and install ONOS.


##Dependences

 * zip(for unzipping files)
 * python-software-properties(for add-apt-repository)
 * karaf
 * maven

The directory of karaf and maven is /root/Applications

##Install
	
	git clone https://github.com/muzixing/onosinstallhelper.git
	cd onosinstallhelper
	sudo ./onosinstallhelper.sh

we can intall specified version ONOS by set the \_version in script. The default verion is 1.0.

Note: This script has only been tested on Ubuntu 12.04 LTS.

#Contributor

 * [muzixing](https://github.com/muzixing)


