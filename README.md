# androidcommands

## Change SD to Internal Memory
### Requirements
 - SD Card Class 10
 - SDK Plataform-Tools(https://developer.android.com/studio/releases/platform-tools)
 
### Step by Step
 - Put android in developer mode
 - Enbale USB Debuger
 - Connect in USB Cable
 - Send command `adb devices`
 - Send command `adb shell`
 - Send command `sm list-disks`
 - Send command `sm set-force-adoptable true`
 - Send command `sm partition disk:179,64 private`
 - Send command `exit`
 - Success!
