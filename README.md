# Amplify-Sample
Initially followed: https://github.com/aws-amplify/docs/blob/master/js/tutorials/building-ionic-4-apps/index.md

Had to make some syntax changes to get it to work

for emulator have to currently run: ionic cordova run ios -- --buildFlag="-UseModernBuildSystem=0"
see: https://github.com/apache/cordova-ios/issues/407

if you're getting an Unknown option: '--buildFlag' error run: npm install -g ionic@latest

Can run with: ionic cordova run ios -- --buildFlag="-UseModernBuildSystem=0"
or: ionic serve

Ran: amplify init before Step 2
-Chose Visual Studio Code
-javascript
-angular
-src
-dist
-npm run-script build
-start command: ionic serve

Setup new user on aWS: Yes


Need to also do: npm install @aws-amplify/ui