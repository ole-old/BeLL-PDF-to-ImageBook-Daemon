
Some scripts for managing the BeLL Demo Box.

# Installation
```
apt-get install imagemagick;
cd /root;
git clone https://github.com/open-learning-exchange/BeLL-PDF-to-ImageBook-Daemon.git;
cp /root/BeLL-Demo/util/init.d/bellpdftoimagebookd /etc/init.d/;
update-rc.d bellpdftoimagebookd defaults;

```
