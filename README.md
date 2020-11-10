# simctlWrapper
Wrapper for Xcode's simctl tool which builds into your Finder app as a context sensitive menu. It can be used for installing and launching apps in the iOS Simulator. Supports launching Watch / WatchKit Apps as well (requires at least version 6.2 of Xcode).

# Installation Process
Just simply copy and paste simctlWrapper into your ~/Library/Services folder. ( So the whole path on your Mac should look something like this : /Users/<userName>/Library/Services/simctlWrapper.workflow )

# Usage
0. Install Xcode on your machine and launch it
1. Create/get a simulator build for an iOS app (built for i386 /+ x86_64 architectures). (It's extension should be ".app")
2. Right click on the ".app" file in Finder and click on simctlWrapper
![Right click on app](https://user-images.githubusercontent.com/7099208/98666710-adc8bd00-234d-11eb-9f0b-f1ef8a2c6127.png)
3. Select the device which you would like to run the app on : 
![Select the device](https://user-images.githubusercontent.com/7099208/98666761-c6d16e00-234d-11eb-9559-edd577091ff5.png)
4. Select the app which you would like to start (note : the watchkitextension isn’t a real selectable option)
![Select the app](https://user-images.githubusercontent.com/7099208/98666819-d81a7a80-234d-11eb-9eed-1c72f186b97b.png)

=>
The selected app starts up in the selected simulator

# Known issues, improvement ideas : 
1. Launching Apple Watch notification is not yet supported
2. There is a known bug on Apple's side related to the Simulator which results in that you can't Install App with WatchKit Extension on iOS 8.1 Simulator with Xcode 6.2
3. Error handling is... Khm... "Not too strong" yet... :)
