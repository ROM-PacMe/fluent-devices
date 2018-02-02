# FluentOS ROM

## Official devices application

Before opening a pull request to add your device into our list of official devices, you should know a few simple things:

### 1. Hosting

Our files are hosted on [Android File Host](http://androidfilehost.com/), this means you must have a developer account to host the builds of your device.

### 2. Changelog
For each new version, you need to upload the changelog to this repository in the device specific folder.

### 4. JSON parameters
| Param | Description | Required |
|--|--|--|
| name | Device name | Yes |
| brand | Device manufacturer | Yes |
| codename | Device codename, eg: falcon | Yes |
| afh_folder | URL of your hidden AFH folder, eg: https://www.androidfilehost.com/?w=files&flid=240377 | Yes |
| maintainer_name | Your name | Yes |

### 5. Build type
You need to add 'export FLUENT_BUILD_TYPE=OFFICIAL' in your build environment so that the OTA app will be included in your build.

### 6. Device tree
Maintainers should upload their device trees on https://github.com/Fluent-Devices 

