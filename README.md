# bad_dragon
Toolkit for working, researching, and screwing around with darwin internals

I'll upload a few here for now, expect a larger drop soon.

device/* binaries run on your device.

## recovery

Kicks your device into recovery mode. 

Need to further experiement with what permissions it needs, likely an entitlement.

* Nearly working on watchOS, codesign is a bitch
* macOS has a seperate API and I have no desire to deal with a reboot the instant it works.
