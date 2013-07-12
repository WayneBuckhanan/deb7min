Notes
=====

 + Run on a freshly installed server under root!
 + Make sure you don't rely on sudo, you'll get locked out as it will be wiped during the cleaning process!

Compatibility
=============

**Operating Systems:**

 + Debian 7 (Wheezy) i686
 + Debian 7 (Wheezy) x86_64

**Platforms:**

 + KVM
 + OpenVZ
 + Physical Hardware
 + Virtualbox
 + VMware
 + Xen HVM

Download
========

Download the script with the following command:

	cd ~; wget --no-check-certificate -O minimal.tar.gz http://www.github.com/WayneBuckhanan/deb7min/tarball/master; tar zxvf deb7min.tar.gz; cd *deb7min*

Instructions
============

You must run this script with options. They are outlined below:

 + For a minimal Dropbear based install: `bash minimal.sh dropbear`
 + For a minimal OpenSSH based install: `bash minimal.sh ssh`
 + To install extra packages defined in the extra file: `bash minimal.sh extra`
 + To set the clock, clean files and create a user: `bash minimal.sh configure`

Credits
=======

 + Primary work by maxexcloo https://github.com/maxexcloo/Minimal.git
 + cedr @ daIRC: General Help
 + DPKG Cleaning: http://www.coredump.gr/linux/debian-package-list-backup-and-restore/
 + miTgiB @ daIRC: Script Help
 + SSH Limiting: http://www.hostingfu.com/article/ssh-dictionary-attack-prevention-with-iptables/
