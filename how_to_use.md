So if you are reading this file it means you have successfully installed the ```vlc-qt``` in your system so let me tell you how you can access it's libraries in your Qt application.

So to use vlc-qt library in your Qt application just go to the ```.pro``` file of your Qt project.
Add the followning line of code to you ```pro``` file.

```
LIBS += -lVLCQtCore -lVLCQtWidgets
INCLUDEPATH += usr/local/include
```
This line are the symlinks which is inserted automatically by ```vlc-qt``` in your system when you installed it. These symlinks are pointing to the directory where your ```vlc-qt```
libraries are stored.

after adding this line into your project just ```clean``` your project and run your application once.
Now after that you will be able to access it's headers file into your project.

for example try to access the following header if you are getting the vlc headers suggestion that means you have done it all right.
```
#include "VLCQtWidgets/WidgetVideo.h"
```
I will also upload one small project using this ```vlc-qt``` soon. Stay tuned with me.

