# darrida fork
I forked this because I'm including it in another bash script I wrote (a first run script after installation GalliumOS and then gnome (among many other things). The only alter here is the removal of the shutdown statement at the end.

# CBFixesAndTweaks (darrida - no change or original text here)
Script to automate CB Fixes and Tweaks
So far this script has been tested on the Toshiba Chromebook 2 (Swanky) running Ubuntu 16.04.
It fixes sound (unfortunately the mic still doesn't work) and keyboard layout.
See http://www.fascinatingcaptain.com/blog/automate-chromebook-fixes-for-linux/

# How to use (darrida - altered link)
Copy and paste these commands in a terminal window and reboot!

cd ~/Downloads; sudo apt-get -y install curl; curl -LOk https://github.com/darrida/CBFixesAndTweaks/archive/master.tar.gz; tar -zxvf master.tar.gz; cd CBFixesAndTweaks-master; sudo -E bash CBFixesAndTweaks.sh
