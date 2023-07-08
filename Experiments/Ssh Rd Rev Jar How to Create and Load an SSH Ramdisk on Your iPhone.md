# How to use Ssh Rd Rev Jar to bypass iCloud activation lock on iPhone 4
 
If you have an iPhone 4 that is locked by iCloud and you don't remember the Apple ID or password, you may be able to use a tool called Ssh Rd Rev Jar to bypass the activation lock and access your device. Ssh Rd Rev Jar is a Java application that creates a custom ramdisk and injects an SSH server into it, allowing you to connect to your iPhone 4 via USB and execute commands on it.
 
**DOWNLOAD ››››› [https://t.co/6VqXgTTKFK](https://t.co/6VqXgTTKFK)**


 
However, this method has some limitations and risks. First of all, it only works on iPhone 4 devices running iOS 7.1.2 or lower. Second, it does not remove the iCloud lock permanently, so you will have to repeat the process every time you reboot your device. Third, it may cause data loss or damage to your device, so use it at your own risk and make sure you backup your data before proceeding.
 
Here are the steps to use Ssh Rd Rev Jar to bypass iCloud activation lock on iPhone 4:
 
1. Download Ssh Rd Rev Jar from [https://github.com/msftguy/ssh-rd/releases](https://github.com/msftguy/ssh-rd/releases) and extract it to a folder on your computer.
2. Download Java Runtime Environment from [https://www.java.com/en/download/](https://www.java.com/en/download/) and install it on your computer.
3. Put your iPhone 4 in DFU mode by holding the power and home buttons for 10 seconds, then releasing the power button and continuing to hold the home button until iTunes detects your device in recovery mode.
4. Open a terminal or command prompt window and navigate to the folder where you extracted Ssh Rd Rev Jar.
5. Type `java -jar ssh_rd_rev04b.jar` and press enter. Wait for the tool to create a custom ramdisk and inject it into your device. You should see a message saying "Waiting for connection" followed by "Connected" and "Shell".
6. Type `mount.sh` and press enter. This will mount the root filesystem of your device.
7. Type `cd /mnt1/Applications/Setup.app` and press enter. This will change the directory to the Setup app folder.
8. Type `mv Setup Setup.bak` and press enter. This will rename the Setup app to Setup.bak, effectively disabling it.
9. Type `reboot` and press enter. This will reboot your device.
10. Your device should now boot up without asking for iCloud activation. However, you will not be able to use any network services or iCloud features on your device. You can only use it as an iPod touch.

If you want to restore your device to its original state, you can do so by following these steps:

1. Put your device in DFU mode again and run Ssh Rd Rev Jar again.
2. Type `mount.sh` and press enter.
3. Type `cd /mnt1/Applications/Setup.app` and press enter.
4. Type `mv Setup.bak Setup` and press enter. This will restore the original Setup app.
5. Type `reboot` and press enter.
6. Your device should now ask for iCloud activation again. You can either enter your Apple ID and password or restore your device using iTunes.

 8cf37b1e13
 
