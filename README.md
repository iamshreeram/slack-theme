# slack-theme
Setting theme of slack

## Installing into Slack application directory based on OS

## For Mac users, 

* `cd` into `/Applications/Slack.app/Contents/` directory
* If you have `wget` installed in your machine, run below command -
  `wget -q -O - https://raw.githubusercontent.com/iamshreeram/slack-theme/master/customizer.js >> Resources\app.asar.unpacked\src\static\ssb-interop.js`
* Restart your `slack` 
* If you don't have `wget`,
  * Copy the content of `https://raw.githubusercontent.com/iamshreeram/slack-theme/master/customizer.js` 
  * Paste it to the last line of `\Resources\app.asar.unpacked\src\static\ssb-interop.js` 


## For Windows or Linux users, 
* Only the base slack installation directory will vary. Other steps would remain same. 
* Debian based Linux Users, Find: `/usr/lib/slack/` (Debian-based)
* Windows: `%homepath%\AppData\Local\slack\`
* We are working on updating further steps. Stay tuned. 
