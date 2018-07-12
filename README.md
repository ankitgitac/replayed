"# replayed" 
Installations:
npm install -g cordova
npm install -g ionic
Configure Platforms:
ionic cordova platform add ios
ionic cordova platform add android

Test:
Web : ionic serve
iOS : 
      ionic cordova build ios
      ionic cordova emulate ios
android : 
    ionic cordova build android
    ionic cordova emulate android 
