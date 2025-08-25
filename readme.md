1. `adb devices` list devices (able to skip adb)
2. `adb shell pm list packages` list all app in device
3. `maestro studio` start maestro studio (support creating simulator device)
4. `maestro start-device --platform android` start device maestro
5. `maestro test --format html --output testResult.html searchFlow` run and get report

*Pull APK to macbook*
1. `adb shell pm path world.notaba.dev` print apk path
2. `adb pull /data/app/~~xyz123/app.dev-abcXYZ==/base.apk /macbook/app.apk` download apk for macbook
