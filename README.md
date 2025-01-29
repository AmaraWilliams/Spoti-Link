To Run:

Physical device option:

1.) Connect device to computer via usb or usb-c

2.) In USB options on your android device, select USB-tethering

3.) Allow USB on your android device

4.) Click "Run" in Android Studio (if you have already ran the app before, it may ask you if you want to reinstall, say "yes")

Emulator option:

1.) In Android Studio, select View > Tool Windows > Device Manager

2.) From here you can click the "+" to add a new "Create Virtual Device"

3.) Choose a device and click "Next"

4.) Choose a system image (install both UpsideDownCakePrivacySandbox and VanillaIceCream so that we can test on both new and older versions)

5.) Install any recommendations (you might have problems if you don't install HAXM. If the file directory for Android SDK Location has a space in it, good luck to you as it WILL cause problems. You can check this by going to Tools > SDK Manager)

6.) You should be able to select the device you want and then click "Run" to start the emulator
