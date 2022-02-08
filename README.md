# Brightness-Changer-Xrandr
This is a script to change the laptop brightness.

It can up the brightness of your display, it can lower the brightness and has the option of night mode that will reduce the blue light from the screen


# How to install it

**Note:** if  `#!/bin/python` doesn't exist, use `#!/bin/python3`

* Go to your downloads folder and open the terminal there.
* Run this following commands:

`git clone https://github.com/lighttigerXIV/Brightness-Changer-Xrandr.git`

`cd Brightness-Changer-Xrandr/`

`chmod +x change-brightness restore-brightness`

`sudo mv change-brightness restore-brightness /usr/local/bin/`

# How to use it


Now that the the scripts are installed you can make the shortcuts for it. (It may be more difficult to override the shortcuts in Gnome )

If you type `change-brightness up` it will up your screen brightness.

If you type `change-brightness down` it will lower your screen brightness.

If you type `change-brightness night` it will activate night mode.

Example in KDE:

![image](https://user-images.githubusercontent.com/35658492/152428238-d0476d34-ce86-420e-a1d0-9eb59caa5944.png)

# Autostart

The next time you login to your user you will lose all the brightness changes made before. 
To restore it just run the command `restore-brightness` or move the restore-brightness script in the .autostart folder.






