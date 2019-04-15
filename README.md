# Personalized Openbox menufiles
### Explanation
The files in /original are retrieved from Openbox, installed as a part of LXDE:
* /etc/xdg/openbox/menu.xml (non-LXDE systems: ~/.config/openbox/menu.xml)
* /var/lib/openbox/debian-menu.xml
* /etc/xdg/openbox/LXDE/menu.xml

### Usage
The files in /personal are my own edited menu's, mostly based on menu.xml (which is the basic menu).

To use these menu's (in this example, the main menu.xml):

```
sudo wget -q http://rawlinktoeditedxml/ -O /etc/xdg/openbox/menu.xml
```
