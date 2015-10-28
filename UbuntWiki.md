#Ubuntu Wiki
**OpenSSH**
~~~
sudo apt-get update
sudo apt-get install openssh-server
sudo emacs /etc/ssh/sshd_config
sudo /etc/init.d/ssh restart
~~~
**Environment**
*Golang*
in ~/.bashrc
~~~
export GOPATH=$HOME/go
export PATH=$PATH:$GOPATH/bin
~~~
*256 color terminal*
in ~/.bashrc
~~~
export TERM=xterm-256color
~~~