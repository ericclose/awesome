# awesome

## Open Source

### Android

#### General

* [ADB](https://developer.android.com/studio/releases/platform-tools#downloads) -- Android Debug Bridge

<details><summary>Details</summary>

> Android SDK Platform-Tools is a component for the Android SDK. It includes tools that interface with the Android platform, primarily [`adb`](https://developer.android.com/studio/command-line/adb) and [`fastboot`](https://android.googlesource.com/platform/system/core/+/master/fastboot/#fastboot).

</details>

* [Magisk](https://github.com/topjohnwu/Magisk/releases/latest) -- Root and modules Manager

<details><summary>Details</summary>

> Magisk is a suite of open source software for customizing Android, supporting devices higher than Android 5.0.
Some highlight features:
>
> * MagiskSU: Provide root access for applications
> * Magisk Modules: Modify read-only partitions by installing modules
> * MagiskBoot: The most complete tool for unpacking and repacking Android boot images
> * Zygisk: Run code in every Android applications' processes

</details>

* [MindTheGapps](https://androidfilehost.com/?w=files&flid=322935) -- third-party GApps distribution

<details><summary>Details</summary>

> Google apps are the proprietary Google-branded applications that come pre-installed with most Android devices, such as the Play Store, Gmail, Maps, etc. Due to licensing restrictions, these apps cannot come pre-installed with LineageOS and must be installed separately. The Google apps are not required to boot or run LineageOS, however many users find them beneficial to take full advantage of the Android ecosystem.
> 
> These apps have been packaged by developers independent of LineageOS, and download links have been provided for your convenience only. It is possible to perform a “backup” of the Google apps on your device and then “restore” them, but this does take additional steps which are not covered here.
>
> The Google apps packages are **not supported** in any way by LineageOS.
>
> source: [Google apps - LineageOS Wiki](https://wiki.lineageos.org/gapps)

</details>

* [payload-dumper-go](https://github.com/ssut/payload-dumper-go/releases/latest) -- Android OTA payload dumper

<details><summary>Details</summary>

> An android OTA payload dumper written in Go.

</details>

* [Barcode Scanner](https://gitlab.com/Atharok/BarcodeScanner) -- Read and generate barcodes

<details><summary>Details</summary>

> Barcode Scanner is a free and open-source app that allows you to read and generate barcodes. This app respects your privacy. It does not contain any trackers and does not collect any data.

</details>

* [Easy Watermark](https://github.com/rosuH/EasyWatermark/releases/latest)

<details><summary>Details</summary>
 
 > Securely, easily add a watermark to your sensitive photos. To prevent them from being leaked or exploited by the BAD GUY.

</details>

* [LibChecker](https://github.com/LibChecker/LibChecker/releases/latest)

<details><summary>Details</summary>
 
 > This app is used to view the third-party libraries used by applications in your device. It can view the ABI architecture of the application's native library (in general, whether the application is 64-bit or 32-bit). It can also view well-known libraries marked by The [Rule Repository](https://github.com/LibChecker/LibChecker-Rules), and can even sort and view them according to the number of libraries references.

</details>

* [Obtainium](https://github.com/ImranR98/Obtainium/releases/latest) -- Get Android app updates straight from the source

<details><summary>Details</summary>

> Obtainium allows you to install and update apps directly from their releases pages, and receive notifications when new releases are made available.

</details>

* [URLCheck](https://github.com/TrianguloY/URLCheck/releases/latest)

<details><summary>Details</summary>

> URLCheck acts as an amazingly customizable and powerful intermediary when opening url links, allowing, among other things: to remove trackers, affiliate links, unnecessary elements, check Hosts, facilitating link holding and sharing, protecting against certain phishing techniques and many more...

</details>

* [Breezy Weather](https://github.com/breezy-weather/breezy-weather/releases/latest) -- A powerful, open-source Material Design weather app

<details><summary>Details</summary>

> Breezy Weather is a free and open-source Android weather app, forked from Geometric Weather, adding new features, sources, modernizing code, fixing bugs, updating dependencies for security reasons, etc., while keep having a smooth user and developer experience in mind.

</details>

* [copy-partitions-20220613-signed.zip](https://mirrorbits.lineageos.org/tools/copy-partitions-20220613-signed.zip) -- Ensure partitions are consistent

<details><summary>Details</summary>

> **Ensuring all firmware partitions are consistent**
>
> NOTE: The steps below only need to be run once per device.
>
> In some cases, the inactive slot can be unpopulated or contain much older firmware than the active slot, leading to various issues including a potential hard-brick. We can ensure none of that will happen by copying the contents of the active slot to the inactive slot.

</details>

---

#### App Store

* [AuroraStore](https://gitlab.com/AuroraOSS/AuroraStore) -- An unofficial FOSS client to Google Play

<details><summary>Details</summary>

> Aurora Store enables you to search and download apps from the official Google Play store. You can check app descriptions, screenshots, updates, reviews, and download the APK directly from Google Play to your device.

</details>

* [Neo Store](https://github.com/NeoApplications/Neo-Store/releases/latest) -- A modern feature-rich F-Droid client

<details><summary>Details</summary>

> The modern and feature-rich F-Droid client for everyone!

</details>

---

#### Network

* [Vernet](https://github.com/TrianguloY/URLCheck/releases/latest) -- Network Analyzer and Monitoring Tool

<details><summary>Details</summary>

> Vernet - Network Analyzer and Monitoring Tool

</details>

* [VPN Hotspot](https://codeberg.org/zinga/VPNHotspot)

<details><summary>Details</summary>

> Connecting things to your VPN made simple. Share your VPN connection over hotspot or repeater. (**root required**)

</details>

* [WiFiAnalyzer](https://github.com/VREMSoftwareDevelopment/WiFiAnalyzer/releases/latest) -- Optimize your WiFi network

<details><summary>Details</summary>

> Optimize your WiFi network, by checking WiFi network status, signal strength and identifying crowded channels using WiFiAnalyzer

</details>

---

#### Motorola-specific

* [motorola_flash_xml](https://gitlab.com/ThomasHastings/motorola_flash_xml) -- Convert Motorola servicefile.xml to fastboot script

<details><summary>Details</summary>

> This is a tool that creates a fastboot script from a Motorola servicefile.xml file.
The original idea comes from [RootJunky on GitHub](https://github.com/rootjunky/Motorola-XML-To-Batch-Script), but it seemed not to work for my Edge 20 Pro. The fastboot-related files are taken from that repo.

</details>

---

### Tools

* [rescuezilla](https://github.com/rescuezilla/rescuezilla/releases/latest) -- The Swiss Army Knife of System Recovery

<details><summary>Details</summary>


> Rescuezilla is an easy-to-use disk cloning and imaging application that's fully compatible with Clonezilla — the industry-standard trusted by tens of millions.
>
> Disk imaging is the process of making a backup of your computer's hard drive which is managed as files stored on an external hard drive, and 'disk cloning' is the process of making a direct copy without needing a third drive for temporary storage.

</details>

* [Tabby](https://github.com/Eugeny/tabby/releases/latest) -- A terminal for a more modern age

<details><summary>Details</summary>
 
 > Tabby (formerly Terminus) is a highly configurable terminal emulator, SSH and serial client for Windows, macOS and Linux.

</details>

* [CPDT](https://github.com/maxim-saplin/CrossPlatformDiskTest/releases/latest) -- Cross Platform Disk Test

<details><summary>Details</summary>
 
 > Measuring storage performance (SSD, HDD, USB Flash etc.) and RAM speed across Windows, macOS and Android devices. Random and sequential throughput (read/write operations) is calculted in MB/s and can be compared in consistent and reliable manner between mobile and desktop platfotms and devices.

</details>

* [LocalSend](https://github.com/localsend/localsend/releases/latest) -- An open-source cross-platform alternative to AirDrop

<details><summary>Details</summary>
 
 > LocalSend is a free, open-source app that allows you to securely share files and messages with nearby devices over your local network without needing an internet connection.

</details>

* [SquirrelDisk](https://github.com/adileo/squirreldisk/releases/latest) -- Disk Usage Analysis Tool

<details><summary>Details</summary>
 
 > The easiest open source app you will ever use to detect huge files. Built with Rust + React (Tauri).
 >
 > Squirreldisk is an open source alternative to softwares like: WinDirStat, WizTree, TreeSize and DaisyDisk.

</details>

* [AB Download Manager](https://github.com/amir1376/ab-download-manager/releases/latest) -- A Download Manager that speeds up your downloads

<details><summary>Details</summary>
 
 > AB Download Manager is a desktop app which lets you manage and organize your download files better than before

</details>

* [NETworkManager](https://github.com/BornToBeRoot/NETworkManager/releases/latest)

<details><summary>Details</summary>
 
 > A powerful tool for managing networks and troubleshoot network problems

</details>

* [Caesium Image Compressor](https://github.com/Lymphatus/caesium-image-compressor/releases/latest)

<details><summary>Details</summary>
 
 > Caesium is an image compression software that helps you store, send and share digital pictures, supporting JPG, PNG, WebP and TIFF formats. You can quickly reduce the file size (and resolution, if you want) by preserving the overall quality of the image.

</details>


* [DBeaver](https://github.com/dbeaver/dbeaver/releases/latest) -- Free universal database tool and SQL client

<details><summary>Details</summary>
 
 > Free multi-platform database tool for developers, SQL programmers, database administrators and analysts. Supports any database which has JDBC driver (which basically means - ANY database).

</details>

* [RustDesk](https://github.com/rustdesk/rustdesk/releases/latest)

<details><summary>Details</summary>
 
 > An open-source remote desktop application designed for self-hosting, as an alternative to TeamViewer.

</details>

---

### Password/Authenticator Manager

* https://github.com/bitwarden

* [Bitwarden](https://github.com/bitwarden) -- Password Manager

<details><summary>Details</summary>
 
 > Bitwarden Password Manager enables businesses and individuals to protect their online data in the face of rising cybercrime threats. Use Bitwarden Password Manager to generate strong, unique passwords for every account you use online.

</details>

* [Ente Auth](https://github.com/ente-io/ente/releases/latest) -- Fully open source authenticators

<details><summary>Details</summary>
 
 > Ente is a service that provides a fully open source, end-to-end encrypted platform for you to store your data in the cloud without needing to trust the service provider. On top of this platform, we have built two apps so far: Ente Photos (an alternative to Apple and Google Photos) and Ente Auth (a 2FA alternative to the deprecated Authy).

</details>

---

### Media

* [BBDown](https://github.com/nilaoda/BBDown/releases/latest) -- Bilibili Downloader

<details><summary>Details</summary>

> 一款命令行式哔哩哔哩下载器. Bilibili Downloader.

 command demo:
 
```batch
 BBDown --encoding-priority hevc -mt --work-dir "D:\Downloads" -p 1 "BV1rG411j7u9"
 ```

</details>

* [Bili.Uwp](https://github.com/Richasy/Bili.Uwp/releases/latest) -- third-party Bilibili UWP app

<details><summary>Details</summary>

> 哔哩 是一款 哔哩哔哩 的第三方应用，使用 UWP 框架开发，是原生的 Windows 应用，支持 Windows 10/11 桌面系统以及版本号在 22000 以上的 XBOX。主打设计和易用性。
>
> 将链接 `ms-windows-store://pdp/?productid=9mvn4nslt150` 复制到浏览器地址栏打开，从 Microsoft Store 下载。

</details>

* [Captura](https://github.com/MathewSachin/Captura/releases/latest) -- Screen recorder

<details><summary>Details</summary>
 
 > Capture Screen, WebCam, Audio, Cursor, Mouse Clicks and Keystrokes.

</details>

---

### Browser Extension

* [Stylus](https://github.com/openstyles/stylus#releases) -- An open source userscript manager

<details><summary>Details</summary>
 
 > Redesign the web with Stylus, a user-style manager. Stylus allows you to easily install themes and skins for many popular sites.

* CSDN - 纯净版 by [otisqzhang](https://uso.kkx.one/style/183456)
* 纯净版 CSDN by [codog-in-github](https://userstyles.world/style/4261/csdn)

</details>

* [Violentmonkey](https://github.com/violentmonkey/violentmonkey) -- An open source userscript manager

<details><summary>Details</summary>
 
 > Violentmonkey provides userscripts support for browsers. It works on browsers with WebExtensions support.

* Custom aliyundrive by [invobzvr](https://cdn.jsdelivr.net/gh/invobzvr/invotoys.js@master/aliyundrive/source.user.js)

</details>

---

### CLI tools

* [zstd](https://github.com/facebook/zstd) -- Fast real-time compression algorithm

<details><summary>Details</summary>
 
 > Zstandard, or `zstd` as short version, is a fast lossless compression algorithm, targeting real-time compression scenarios at zlib-level and better compression ratios. It's backed by a very fast entropy stage, provided by [Huff0 and FSE library](https://github.com/Cyan4973/FiniteStateEntropy).

demo:

```bash
# Use the -v (verbose) option to see detailed output about zstd’s progress as it compresses your file(s).
tar -I 'zstd -v' -cvf example.tar.zst example/

# To decompress a tar archive with the .tar.zst file extension, use the following command syntax.
tar -I zstd -xvf example.tar.zst
```

</details>

* [CloudflareSpeedTest](https://github.com/XIU2/CloudflareSpeedTest)

<details><summary>Details</summary>

demo:

```batch
@echo off

CloudflareST.exe -f "%~dp0ip.txt" -dn 20 -o "" -sl 5 -tl 300

PAUSE
```

</details>

---

## Closed Source

### Android

* [NetMonster](https://play.google.com/store/apps/details?id=cz.mroczis.netmonster) -- Mobile network monitoring app

<details><summary>Details</summary>
 
 > NetMonster collects, shows and stores information about nearby cell towers. Each tower has its unique set of identifiers and NetMonster will show you them. In select areas and countries precise locations are available.
 >
 > NetMonster is based on open-source library [NetMonster Core](https://github.com/mroczis/netmonster-core)

</details>
