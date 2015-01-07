# Konotor PhoneGap/Cordova Plugin
### Platform Support

This plugin supports PhoneGap/Cordova apps run on iOS.

## Installation
#### Automatic Installation using PhoneGap/Cordova CLI (iOS)

1. Install this plugin using PhoneGap/Cordova cli:

        phonegap plugin add https://github.com/rkranjith/konotor-plugin.git --variable APP_ID="YOUR_APP_ID" --variable APP_KEY="YOUR_APP_KEY"
        
                                    or
                                    
        cordova plugin add https://github.com/rkranjith/konotor-plugin.git --variable APP_ID="YOUR_APP_ID" --variable APP_KEY="YOUR_APP_KEY"

        
2. Add this script tag to your index.html:

        <input id="KonotorMenu" type="button" value="Talk To Us" onclick="konotor.launchKonotorScreen();"></input>
