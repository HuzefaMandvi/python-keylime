Using python-keylime RPM

OS: CentOS 7

Dependencies:
- yum update
- yum install epel-release
- python2.7.10+
    - install as indicated https://danieleriksson.net/2017/02/08/how-to-install-latest-python-on-centos/
    - edit /etc/sudoers to disable secure path (allows sudo to use python2.7)
    - install pip2.7 for sudo

Install:
- sudo yum localinstall --nogpgcheck python-keylime-1.2.1.noarch.rpm
