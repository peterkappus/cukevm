# cukevm
The purpose of this repo is to study how to run cucumber tests on a stand-alone VM using PhantomJS (without using docker).


You'll need to install maven (mvn):
http://apache.mirror.anlx.net/maven/maven-3/3.5.3/binaries/apache-maven-3.5.3-bin.tar.gz
(download, unzip, symlink the mvn file to something in your path)
e.g. `sudo ln -s /app/apache-maven-3.5.3/bin/mvn /usr/bin/mvn`

You'll also need 
## Troubleshooting

Can't mount a local folder?
See:
https://www.megajason.com/2017/06/10/install-virtualbox-guest-additions-on-centos-7/

OR: https://sobo.red/2017/04/27/installing-virtualbox-guest-additions-on-centos-7/
Summary:
1. Download the guest additions ISO
2. Stop the VM and mount the ISO into the VM using the Virtualbox UI
3. Restart the vm... Run some commands (see link above)
