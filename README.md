# Konotor Cordova Plugin
### Platform Support

This plugin supports Cordova apps run on iOS.

## Installation
#### Automatic Installation using Cordova CLI (iOS)

1. Install this plugin using Cordova cli:

        cordova plugin add https://github.com/rkranjith/konotor-plugin.git --variable APP_ID="YOUR_APP_ID" --variable APP_KEY="YOUR_APP_KEY"
        
2. Add this script tag to your index.html:

        <input id="KonotorMenu" type="button" value="Talk To Us" onclick="konotor.launchKonotorScreen();"></input>
