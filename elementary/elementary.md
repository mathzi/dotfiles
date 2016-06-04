# :wrench: `elementary configs (~soon as a script~)`

## :runner: `first steps`

```
1. add canonical partners
2. sudo apt-get update && sudo apt-get upgrade
3. ~reboot system~
4. sudo apt-get install ubuntu-restricted-extras
```

## :pushpin: `some utils`

###### `sudo apt-get install vlc libreoffice skype gimp transmission rar synaptic steam`

###### `git`

```
sudo add-apt-repository ppa:git-core/ppa
sudo apt-get update
sudo apt-get install git
```

###### `github`
`generate git ssh key`

###### `chrome`

```
sudo apt-get install libxss1 libappindicator1 libindicator7
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome*.deb
```

###### `java`

```
sudo apt-get install icedtea-7-plugin openjdk-7-jre
sudo add-apt-repository ppa:webupd8team/java
sudo apt-get update
sudo apt-get install oracle-java8-installer
```


###### `spotify`

```
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys BBEBDCB318AD50EC6865090613B00F1FD2C19886
echo deb http://repository.spotify.com stable non-free | sudo tee /etc/apt/sources.list.d/spotify.list
sudo apt-get update
sudo apt-get install spotify-client
```

###### `ruby with rvm`

```
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
\curl -sSL https://get.rvm.io | bash -s stable --ruby
```

###### `mkvmerge`

```
sudo add-apt-repository "deb http://www.bunkus.org/ubuntu/trusty/ ./"
wget -O - http://www.bunkus.org/gpg-pub-moritzbunkus.txt | sudo apt-key add -
sudo apt-get update
sudo apt-get install mkvtoolnix mkvtoolnix-gui
```

## :milky_way: `nvidia graphics`

###### `ppa:graphics-drivers/ppa`

## :computer: `style settings`

###### `tweaks`

```
sudo add-apt-repository ppa:mpstark/elementary-tweaks-daily
sudo apt-get update
sudo apt-get install elementary-tweaks
```

###### `icons`
`numix-circle`

###### `gtk`
`iris-master`

###### `files`
`single click = false`

###### `terminal`
`zenburn opacity 100%`
