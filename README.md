## byobu  
  
byobu is a script that launches a text based window manager  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/byobu/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install byobu
```  

Fedora Based:

```shell
yum install byobu
```  

Arch Based:

```shell
pacman -S byobu
```  

MacOS:  

```shell
brew install byobu
```
  
```shell
mv -fv "$HOME/.config/byobu" "$HOME/.config/byobu.bak"
git clone https://github.com/dfmgr/byobu "$HOME/.config/byobu"
```
  
<p align=center>
  <a href="https://github.com/dustinkirkland/byobu" target="_blank" rel="noopener noreferrer">byobu github</a>  |  
  <a href="https://www.byobu.org" target="_blank" rel="noopener noreferrer">byobu site</a>
</p>  
