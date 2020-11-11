fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## Android
### android readVersion
```
fastlane android readVersion
```
Read flutter app version info from local(pubspec.yaml)
### android fetchVersion
```
fastlane android fetchVersion
```
Fetch flutter app version info from google play track
### android test
```
fastlane android test
```
Runs all the tests
### android beta
```
fastlane android beta
```
Deploy a new version to the Google Play Internal
### android alpha
```
fastlane android alpha
```
Deploy a new version to the Google Play Alpha
### android open
```
fastlane android open
```
Deploy a new version to the Google Play Open
### android deploy
```
fastlane android deploy
```
Deploy a new version to the Google Play Production
### android track_promote
```
fastlane android track_promote
```
Promote track to another track
### android chatbot_telegram
```
fastlane android chatbot_telegram
```
Telegram chatbot send a message

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
