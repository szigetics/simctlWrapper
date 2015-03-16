# simctlWrapper
Wrapper for Xcode's simctl tool which builds into your Finder app. It can be used for installing and launching apps in the iOS Simulator.

# Installation Process
Just simply copy and paste simctlWrapper into your ~/Library/Services folder. ( So the whole path on your Mac should look something like this : /Users/<userName>/Library/Services/simctlWrapper.workflow )

# Usage
0. Install Xcode on your machine and launch it
1. Create/get a simulator build for an iOS app (built for i386 /+ x86_64 architectures). (It's extension should be ".app")
2. Right click on the ".app" file in Finder.
3. Click on simctlWrapper
4. Go through the simple process

# Known issues, improvement ideas : 
1. Launching Apple Watch notification is not yet supported
2. Error handling is... Khm... "Not too strong" yet... :)