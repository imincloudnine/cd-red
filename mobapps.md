### flutter and dart and how to dump hours in here

### flutter version
```
flutter doctor
flutter doctor -v
```

### devices and emulators
```
flutter devices
flutter emulators
adb emulators

# adb kill and start
adb kill-server
adb start-server
```

### start the emulator and run flutter
```
# start emulator
flutter emulators --launch <emulator name>
# or
emulator -adv <emulator name>

# in another terminal, in your project folder
flutter run

# to run specific file
flutter run --target=lib/file.dart
```
