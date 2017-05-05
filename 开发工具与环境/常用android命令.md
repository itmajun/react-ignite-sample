#sdk 常用命令

1. adb devices
2. adb reverse tcp:8081 tcp:8081
3. adb shell input keyevent 82

tips: 如果`adb devices ` 查出很多设备，在运行时候会提示设备太多，可以通过 `adb -s emulator-5556 shell input keyevent 82` 调用设备menu. 