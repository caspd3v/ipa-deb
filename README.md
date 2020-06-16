# iPA-Deb

This is a tool to turn any ipa into an installable deb file for jailbroken iOS devices.

## Setup

1. Make a folder and put ipa-deb.py & your iPA in the folder.
2. Open Terminal and cd into thet folder.
3. Give the script permissions shown below
```bash
chmod +x ipa-deb.py
```

## Requirements

1. MacOS or a jailbroken iOS device.
2. Python3
3. Install DPKG

## How To Use

```bash
python3 ipa-deb.py
```

1. Type the ipa file name.
Example:
```bash
ipaname
```
2. Leave it running until it prompts your to enter the control file fields.

## Control File
Bundle ID:
Example:
```bash
com.example.app
```
Name:
Example:
```bash
App Name
```
Varsion:
Example:
```bash
1.0.0
```
Description:
Example:
```bash
This is my super cool app!
```
Maintainer:
Example:
```bash
Username
```
Auther:
Example:
```bash
Username
```

## Final Thoughts

This tool makes it easy to create packages and it takes no time at all :)


## Licence

[Casp's Website](https://casp.dev)