# frida-java

Java runtime interop from Frida. This module is bundled with Frida and exposed
through the global named `Java`.

## Running the test-suite

### Dependencies

- Android SDK Platform-Tools >= 25.0.3
- Android NDK r13b

With environment configured accordingly:

```sh
$ export ANDROID_SDK_ROOT=~/Library/Android/sdk
$ export ANDROID_NDK_ROOT=/usr/local/opt/android-ndk-r13b
```

### Run

```sh
$ make check
```

### Debug

```sh
$ make check-gdb
```

### Auto-run tests on JavaScript change

```sh
$ make develop
```
