# amd64-arm
Set up an emulated Debian 64-bit (amd64) environment (Stretch, Buster doesn't work at the moment with emulation) on an ARM computer/SBC. Requires Debian or one of its derivatives like Raspberry Pi OS (previously Raspbian), Ubuntu, Kali Linux etc to be installed.

## Tested derivatives of Debian on which amd64-arm can be set up

1. Raspberry Pi OS (previously Raspbian) Buster
2. Ubuntu Server 20.04

## Untested derivatives of Debian (might work)

1. Kali Linux

## Tested hardware

1. Raspberry Pi 4B

## Untested hardware

1. A Mac computer using Apple Silicon with an ARM Debian VM running on it.

# Setup i386-arm on your ARM computer/SBC

You need to download amd64-arm at https://raw.githubusercontent.com/RudraSwat/amd64-arm/master/amd64-arm and run the below commands in the terminal:

```
chmod +x <FULL_PATH_TO_DOWNLOADED_FILE>
sudo <FULL_PATH_TO_DOWNLOADED_FILE>
```

# Wiki

The wiki is available at https://github.com/RudraSwat/amd64-arm/wiki.
