# ubuntu configurations

## Customize

### language
edit: `vim /etc/default/locale`

```
LANG="en_US.UTF-8"
#LANG="pt_BR.UTF-8"
LANGUAGE="en_US:en:en"
#LANGUAGE="pt_BR:pt:en"
```
## tools

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
```$ vim .bashrc```
add at the end:
```
exec zsh
```
plugins:


