<p align="center">
  <img src="https://i.imgur.com/7MhYAxh.png" />
</p>

# PixelPlusUI [![Download PixelPlusUI Builds](https://img.shields.io/sourceforge/dt/pixelplusui-project.svg)](https://ppui.site/download)
### - Your Requirements Our Goals

PixelPlusUI is an another aftermarket aosp ROM Minimal UI & close to Stock Android ROM. What differentiates us from the rest, you ask? LET'S FIND OUT. Our main aim is to give user a better experience without compromising quality of Android experience so that no one struggles in any kind of difficulties while using their device. It brings a better UI/UX to Android with a seamless experience coupled with customisations and user security. Inshort its perfectly balaced between Great Performance, Security, Stability, Minimal UI & Awesome features including pixel goodies. Join us now and start enjoying the beauty of stock Android. Build and enjoy PixelPlusUI on your respective devices!

To get started, you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).

## Create a directory for the source files

* You can name this directory however you want, just remember to replace
* WORKSPACE with your directory for the rest of this guide.
* This can be located anywhere (as long as the fs is case-sensitive)

```bash
mkdir WORKSPACE
cd WORKSPACE
```

### Install Repo in the created directory

>> [Hint: This might take a long time]

```bash
repo init -u https://github.com/PixelPlusUI/manifest -b tiramisu
```

>> [Hint: Want to save some space ? Then use this]

```bash
repo init --depth=1 -u https://github.com/PixelPlusUI/manifest -b tiramisu
```

### Download the source
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash
# Set up environment
. build/envsetup.sh
# Choose a target
lunch aosp_$device-userdebug
# Build the code
mka bacon -jX
```

![Credit](https://i.imgur.com/Jm0O4d1.jpg "Credit")

 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)

![Support and Donation](https://i.imgur.com/vfXdZIO.png "Support and Donation")

### Adding Support
 - For adding your device to the list of OFFICIALLY supported devices, you need to contact us on Telegram profiles below with device name and device, vendor, kernel trees.
* [**Saurav**](https://t.me/ugly_kid_af) 


Now if you need to contact us, well, you may ask in our [Telegram](https://t.me/ppuichat) Support Group, ~~we may or may not answer.~~

 * [**Telegram Announcements Channel**](https://t.me/ppuich)
 * [**Our OFFICIAL Website**](https://ppui.site/)
 * [**Our Team**](https://ppui.site/team)
 * [**Currently supported devices**](https://ppui.site/download)
 * [**Changelog**](https://ppui.site/changelog)
 * [**Telegram Discussion Group**](https://t.me/ppuichat)
 * [**Twitter**](https://twitter.com/pixelplusui)

### Do consider donating or buying me a coffee on Paypal if you want to appreciate our work or join us on Patreon for sustainable support and early build access.

```bash
Patreon : https://www.patreon.com/join/uglykid24
```
```bash
GPAY UPI ID: dwarmachine24@oksbi
```
```bash
PAYPAL: https://www.paypal.me/uglykid24
```

# Happy Building :)

