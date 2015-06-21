# SuperUser

Hello :) Welcome to the SuperUser wiki!

This is the su binary for Superuser on Android.

Any app that requires root access must call this binary in order to be given root access.

This binary is tested and targeted for Android 4.2+.

Building the su binary
1.Checkout the code.

2.Set environment variables :

  export NDK_ROOT="/home/surya/Work/android-ndk-r10d"
  
  export NDK_PROJECT_PATH="/home/surya/Work/super-user"
  
  export PATH="$PATH:$NDK_ROOT"
  
3.Place this code in a jni folder inside "super-user" directory.

4.Run ndk-build

5.Done..Your SU binary is ready.Have fun :)

