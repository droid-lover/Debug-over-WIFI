# Debug-over-WIFI
how to debug your code over wifi on your android device (without USB)


these are the commands you need to run :-

    adb devices
    adb tcpip 5555
    adb connect 192.168.20.150:5555
    adb devices


In case adb is not there Just Install from here 

Install homebrew-
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
Install adb-
brew cask install android-platform-tools
