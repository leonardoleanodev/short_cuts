# Ubuntu configurations

## Customize

### language
edit: `vim /etc/default/locale`

```
LANG="en_US.UTF-8"
#LANG="pt_BR.UTF-8"
LANGUAGE="en_US:en:en"
#LANGUAGE="pt_BR:pt:en"
```

## Tools

### OhMyZsh
tool for shurtcuts in terminal, it add agility in coding or executing comands in terminal
ref: https://ohmyz.sh/
preseted comands for configuration:
```
$ sudo apt-get update
$ sudo apt-get install zsh
$ wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh
$ sudo sh install.sh
```
configure:
edit ".bashrc"
`
$ vim .bashrc
`
add at the end:
`
exec zsh
`
plugins:

## apt-get packages

### virtualenv
virtual enviroment 
```
$sudo apt-get install virtualenv
```
common use setting python3.7?
```
$virtualenv --python=python3.7 venv
```
## Use full python tools

I have to make a requirement for this
```
$pip install flake8
$pip install requests
```

## Usefull commands 

**check ubuntu version:**
```
cat /etc/os-release
```

**awk pattern scanning and processing language:**
```
awk -F'<separator>' '{ print $<index to be listed> }' <dir>
```
ref: https://www.cyberciti.biz/faq/bash-scripting-using-awk/

## DEV-IDE

https://code.visualstudio.com/docs/setup/linux

## Docker installation
Container generator and administrator
https://docs.docker.com/install/linux/docker-ce/ubuntu/

## References to be agregated and studie:

<p>https://linuxconfig.org/bash-scripting-tutorial-for-beginners
(Relative vs Absolute Path)
<p>https://aurelio.net/shell/canivete/
<p>https://linoxide.com/linux-how-to/commands-clear-linux-terminal/
<p>https://docs.authlib.org/en/latest/client/oauth2.html 


