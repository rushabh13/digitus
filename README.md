# Digitus

Digitus is a library designed to make Fingerprint authentication using Nexus Imprint easier for developers.
On API levels below Marshmallow, it will fall back to a password dialog.

![Art](https://github.com/rushabh13/digitus/blob/master/art.jpg)

**Note**: this library is powered by [material-dialogs](https://github.com/afollestad/material-dialogs),
depending on this library will automatically depend on Material Dialogs. 

# Testing Fingerprints from an Emulator

The stock Android emulator allows you to test Nexus Imprint. If you create a Nexus 5X emulator,
you can simulate a finger pressing against the reader using this Terminal command:

```shell
adb -e emu finger touch finger-id
```

*finger-id* would be replaced with a number, e.g. 1, 2, 3, etc.


# Tutorials

This document will be updated with a tutorial once I finalize this library's APIs.
