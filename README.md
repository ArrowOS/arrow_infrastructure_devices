## How to apply for official maintainership

### The device maintainer and the device itself need to meet certain requirements:

#### Device maintainer:
- Applicant must have interest in **actively maintaining** the ROM for the device, not just build and forget.
- Applicant should be having good knowledge of the use of GitHub and Gerrit.
- A proper commit history with authorship should be maintained for all of the commits being done or cherry-picked. We have zero-tolerance towards [‘KANG’](https://www.urbandictionary.com/define.php?term=Kang) and one found guilty will be removed immediately.
- It is highly desired that the applicant should have a Telegram Account to be in touch with the team.

#### Device requirements
-   We prefer SeLinux to be enforcing, but this is something we will evaluate based on the device and the applicant.
-   All of the Device sources must be Open Sourced. No private source shall be encouraged!
-   All the main device functions i.e, [Camera,Data, Voice Calling,WiFi, Hotspot, Bluetooth (and Fingerprint, NFC, Sensors etc if applicable)] should all be working to be fit for the use as a daily driver.
-   Device sources should be maintained to not have any errors during upstream updates & changes for the proper functioning of automated Jenkins builds.

### How to apply for official maintainership
For applying for maintainership, you must create a GitHub issue on the **[arrow_infrastructure_devices](https://github.com/ArrowOS/arrow_infrastructure_devices)** repository, preferably using the following template:

- Title: `Official maintainership application for Device Name (codename)`
- Content:
```
Name: 'Your name'
Telegram: 'Link to your telegram account'
E-mail: 'E-mail you want to use for Slack'

Device: 'Device Name (codename)'
SELinux status: 'Enforcing/Permissive'

Device sources:
- android_device_brand_codename: 'Link to android_device_brand_codename'
- android_kernel_brand_codename: 'Link to android_kernel_brand_codename'
(...) Additional device-side repositories
- android_vendor_brand_codename: 'Link to android_vendor_brand_codename'

(Optional) Additional source patches that your device /needs/
```

You will need to attach two screenshots, one of the 'About phone' section of your ArrowOS build, and another of the 'Build completed successfully' terminal after building the package.

You may also add any other additional information that you deem necessary.