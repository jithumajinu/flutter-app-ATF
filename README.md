# flutter-app-ATF

Installation in MacOS
To install Flutter on MacOS.

Step 1 − Go to URL, https://flutter.dev/docs/get-started/install/macos and download latest Flutter SDK.

Step 2 − Unzip the zip archive in a folder.

Step 3 − Update the system path to include flutter bin directory (in vim ~/.bash_profile file). default shell may be zsh so use  vim ~/.zprofile

in my installation path is  /Users/xyzzz/Documents/Dev-Application/flutter/bin 

 $ vim ~/.zprofile     
 
 i for insert mode. then paste below command  
 export PATH="$PATH:/Users/xyzzz/Documents/Dev-Application/flutter/bin"
 
 then  :wq for save and exit;
 
 Step 4 − $ which flutter
           /Users/xyzzz/Documents/Dev-Application/flutter/bin/flutter
           
 Step 5 - flutter doctor
 
  install what ever recomented by flutter doctor.
  
  ➜  ~ flutter doctor
Doctor summary (to see all details, run flutter doctor -v):
[✓] Flutter (Channel stable, 1.22.0, on Mac OS X 10.15.6 19G2021, locale en-JP)
[✓] Android toolchain - develop for Android devices (Android SDK version 30.0.2)
[✓] Xcode - develop for iOS and macOS (Xcode 11.4.1)
[✓] Android Studio (version 4.0)
[!] IntelliJ IDEA Community Edition (version 2019.3.1)
    ✗ Flutter plugin not installed; this adds Flutter specific functionality.
    ✗ Dart plugin not installed; this adds Dart specific functionality.
[✓] VS Code (version 1.49.1)
 
[!] Connected device                          
    ! No devices available

! Doctor found issues in 2 categories.

-----------------------------------------
  
