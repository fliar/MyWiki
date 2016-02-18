#Ubuntu Wiki
**Command**<br>
*change owner*
sudo chown user:group file<br>
**OpenSSH**<br>
~~~
sudo apt-get update
sudo apt-get install openssh-server
sudo emacs /etc/ssh/sshd_config
sudo /etc/init.d/ssh restart
~~~
**Environment**<br>
*Golang*<br>
in ~/.bashrc
~~~
export GOPATH=$HOME/go
export PATH=$PATH:$GOPATH/bin
~~~
*256 color terminal*<br>
in ~/.bashrc
~~~
export TERM=xterm-256color
~~~
*apt-get use proxy*<br>
in /etc/apt/apt.conf
~~~
Acquire::http::Proxy "http://111.111.111.111:11111";
~~~
*dns config*<br>
temp: in  /etc/resolv.conf, add
~~~
nameserver 114.114.114.114
~~~
permanent: in /etc/network/interfaces
~~~
dns-nameservers X.X.X.X Y.Y.Y.Y Z.Z.Z.Z
~~~
then run
~~~
sudo ifdown eth0 && sudo ifup eth0
~~~
*remove kai & ming font*<br>
~~~
sudo apt-get purge fonts-arphic-ukai 
sudo apt-get purge fonts-arphic-uming 
~~~
