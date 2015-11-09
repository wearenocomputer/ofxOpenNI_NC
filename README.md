# ofxOpenNI_NC 
    
 
Just like we do, many artists still use the older Kinect for Xbox360 in their projects.<br>
While there are still many ofxOpenNI add-ons out there, we noticed that many of them are out-dated and do not work anymore.

This is working version hacked together with copies of the libraries we had lying around and the [gameoverhack repo](https://github.com/gameoverhack/ofxOpenNI/tree/v1.0)

This add-on has been tested with of 0.8.4 and xcode 7.1 on osx Yosemite 10.10.5

INSTALLATION
============

* put the files in your add-on folder.
* copy the folder named openni in the folder mac of the add-on to the data folder of your app.<br>
Your app structure should look like this:<br>
-apps/myApps/nameofmyapp/bin/data/openni<br>
   -config<br>
   -lib<br>
* in Xcode add the library libOpenNI.dylib to your project with -> Build Phases -> Link Binary with Libraries. 
* in Xcode add the library search path to the folder that contains the libOpenNI.dylib


        




