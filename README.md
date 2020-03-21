# PIXEL64-RPI

```
apt-get install gnupg wget -y
wget https://chainsx.github.io/PIXEL64-RPI/pub.key
gpg --import pub.key
gpg --export --armor | apt-key add -
rm pub.key
touch /etc/apt/sources.list.d/chainsx.list
echo "deb https://chainsx.github.io/PIXEL64-RPI/ ./" >> /etc/apt/sources.list.d/chainsx.list
echo "Done."
apt-get update
apt-get install xinit --no-install-recommends
apt-get install xserver-xorg --no-install-recommends
apt-get install raspberrypi-ui-mods
```
