# Adorn : 
        A one click support of black code formatter for IDEs and text editors.


### Requirements
* [Gedit](https://wiki.gnome.org/Apps/Gedit)

### Demo

![Adorn Demo](Adorn.gif)

### General Info
 * currently there is support for gedit only
 * Tested for root user only so A permission error may arise if used by another user.
 * For now run gedit with sudo only ``sudo gedit filename``


### Install
* Install with script
  * Open terminal and execute `sudo ./install.sh`
  
* Manual Install
  * Copy all contents of **folder that matches your gedit version** to path `~/.local/share/gedit/plugins/`
  * Install **python3** and **pip3** by `sudo apt-get install python3-all-dev python3-pip`
  * Install **black** by `sudo pip3 install black`


