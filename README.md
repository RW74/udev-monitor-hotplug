# Description

I was tired of having to configure manually the disposition of my monitors when I plugged them in
I decided to write this script that define custom behaviour when monitor are plugged in

You might want to adapt the script to your needs ./usr/local/bin/monitor-hotplug.sh 

I was inspired by http://stackoverflow.com/questions/5469828/how-to-create-a-callback-for-monitor-plugged-on-an-intel-graphics

## Installation
sudo cp ./usr/local/bin/monitor-hotplug.sh /usr/local/bin/
sudo cp etc/udev/rules.d/99-monitor-hotplug.rules  /etc/udev/rules.d/

## License 

I'm not responsible of the effect of this script on your computer

Feel free to do whatever you want with it :-)
