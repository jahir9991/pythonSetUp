# pythonSetUp

$ sudo apt-get update

$ sudo apt-get -y upgrade
 
$python3 -V
>Python 3.5.2

$ sudo apt-get install -y python3-pip

$ sudo apt-get install build-essential libssl-dev            libffi-dev python-dev

$ sudo pip install virtualenv

$ mkdir ~/.virtualenvs

$ sudo pip3 install virtualenvwrapper

$ code ~/.profile

And add the following lines:

export WORKON_HOME=$HOME/.virtualenvs
export PROJECT_HOME=$HOME/Devel
export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3
export VIRTUALENVWRAPPER_VIRTUALENV=/usr/local/bin/virtualenv
source ~/.local/bin/virtualenvwrapper.sh
