# React Native + Detox

This repo is a clean install of react native with the latest version of Wix Detox installed. The purpose of the repo is to highlight an issue with Android release mode in the current version of RN.

Recreate the issue by building a release version of the app.

```bash
$ detox build -c android.emu.release
```

Run the tests

```bash
$ detox test -c android.emu.release
```

If you need to create an emulator run:

```
$ yarn create-emulator
```

Test will hang until it times out
