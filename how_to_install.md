In order to use the VLC-QT in your Qt application first you need to install it in your system.

To install the VLC-Qt in your Linux system first you need to clone it's repository in your system. So first go to any location of your system and then clone it's git repository.
You need to execute the following command to clone the repository.

```
git clone https://github.com/vlc-qt/vlc-qt.git
```

You can also visit the official vlc-qt repository to take repository url from there (https://github.com/vlc-qt/vlc-qt)

after clonning the repository next you need to install this in your system for which you need to follow the instruction written in 
```
BUILDING.md
```
file in that repository.

Here I am just explaining the building process of Linux only, but you can find windows and macos build instruction in building.md file there.

So after clonning go to that clone repository folder, It means go inside the folder of the reposiotry you have cloned.

Suppose after clonning the repository you got the folder ```vlc-qt``` so just go inside that directory after that just open your terminal from that location and run the following commands to build
the ```vlc-qt``` in your linux system.

### Linux
Install requirements from your distribution's repository.
Supported generators are `make` and `ninja`.

Make example:
```
$ mkdir build
$ cd build
$ cmake .. -DCMAKE_BUILD_TYPE=Debug
$ make -j8
$ make install
```	
[ NOTE:- Make sure you have ```cmake``` installed in your system ]

After running all the above commands successfully just reboot your system.

You have sucessfully installed the vlc-qt in your system. Now in order to connect it with your Qt application just read How_To_Use_In_Qt.md file

