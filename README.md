# Softether Auto Install Multi Platform<br />
* Softether Auto Install Script for multi platforms<br />
* An open source VPN project from University of Tsukuba Japan<br />
* Centos 6 or 7 x64
* Debian 8 (jessie) (Not compatible with Debian 9 (stretch) x64 - compilation error)
* Ubuntu 14, 15, 16, 17 x64
# Instruction<br />

* Choose your desired platform folder<br />
* Download installer.sh using wget or transfer to your root directory using ftp<br /><br />

* Install wget first<br /><br />

* For centos and fedora<br />
$ sudo yum install wget -y<br /><br />

* For debian and ubuntu<br />
$ apt-get install wget -y<br /><br />

* Download and install the installer.sh by executing the commands below<br /><br />

* For centos and fedora<br />
$ wget https://raw.githubusercontent.com/jaysonvelagio/SoftetherAutoInstallMultiPlatform/master/Centos/installer.sh<br />
$ chmod +x installer.sh<br />
$ ./install.sh<br /><br />

* For debian and ubuntu<br />
$ wget https://raw.githubusercontent.com/jaysonvelagio/SoftetherAutoInstallMultiPlatform/master/Debian%20and%20Ubuntu/installer.sh<br />
$ chmod +x installer.sh<br />
$ ./install.sh<br />

# VPN server commands<br />
* /etc/init.d/vpnserver start - to start<br />
* /etc/init.d/vpnserver restart - to restart<br />
* /etc/init.d/vpnserver stop - to stop<br /><br />

* vpncmd is at /usr/local/vpnserver



