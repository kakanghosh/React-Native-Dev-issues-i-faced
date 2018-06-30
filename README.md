# React-Native-Dev-issues-i-faced

# Compress APK size, migrate expo to react native

https://medium.com/@aswinmohanme/how-i-reduced-the-size-of-my-react-native-app-by-86-27be72bba640

# Solved ENOSPC error
https://stackoverflow.com/questions/22475849/node-js-error-enospc/32600959#32600959

# Generate APK
https://stackoverflow.com/questions/35935060/how-can-i-generate-an-apk-that-can-run-without-server-with-react-native

# Generate Universal APK and Two architechture 
# Splits abs (app/build.gradle)
splits {
        abi {
            enable true
            reset()
            include 'x86', 'armeabi-v7a'
            universalApk true
        }
    }
 remove ndk (app/build.gradle)
 
 # add google() (android/build.gradle) in all project

# Could not find com.android.tools.lint:lint-gradle Android Studio 3
https://stackoverflow.com/questions/46972122/could-not-find-com-android-tools-lintlint-gradle-android-studio-3


