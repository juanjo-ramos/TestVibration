# TestVibration
Problem getting the device to vibrate on a Swift project running on iPhone 5s/6 with iOS 9.2 from Xcode 7.2

# Description
To my understanding, both `AudioServicesPlayAlertSound(SystemSoundID(kSystemSoundID_Vibrate))` and `AudioServicesPlaySystemSound(SystemSoundID(kSystemSoundID_Vibrate))` should make the device vibrate. In particular, I have used the latter many times in its Objective-C form without any issues.

However, I cannot get this code to make neither an iPhone 5s or iPhone 6 produce a vibration. Both devices were running iOS 9.2 and the app built with Xcode 7.2

Tapping on `Vibrate 1` has never worked for me. But after uninstalling and re-installing the app a few times, tapping on `Vibrate 2` did make the phone vibrate ?!??!!

If somebody could point me to what I'm missing it would be greatly appreciated but I'm starting to think this is bug.
