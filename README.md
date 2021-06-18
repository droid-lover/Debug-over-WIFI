# Debug-over-WIFI
how to debug your code over wifi on your android device (without USB)

I wrote a blog on it explaining how you can do this.


<a href="https://medium.com/native-mobile-bits/debug-your-apps-without-cable-99452daf8755">Check blog here. :) </a> 

these are the commands you need to run :-

    adb devices
    adb tcpip 5555
    adb connect 192.168.20.150:5555 . (adb connect your_device_ip:port)
    adb devices


In case adb is not there Just Install from here 

    Install homebrew-
    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    Install adb-
    brew cask install android-platform-tools
