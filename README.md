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

* [copy-partitions-20220613-signed.zip](https://mirrorbits.lineageos.org/tools/copy-partitions-20220613-signed.zip) -- Ensure partitions are consistent

<details><summary>Details</summary>

> **Ensuring all firmware partitions are consistent**
>
> NOTE: The steps below only need to be run once per device.
>
> In some cases, the inactive slot can be unpopulated or contain much older firmware than the active slot, leading to various issues including a potential hard-brick. We can ensure none of that will happen by copying the contents of the active slot to the inactive slot.

</details>

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
 
 > Tabby (formerly Terminus) is a highly configurable terminal emulator, SSH and serial client for Windows, macOS and Linux

</details>

* [CPDT](https://github.com/maxim-saplin/CrossPlatformDiskTest/releases/latest) -- Cross Platform Disk Test

<details><summary>Details</summary>
 
 > Measuring storage performance (SSD, HDD, USB Flash etc.) and RAM speed across Windows, macOS and Android devices. Random and sequential throughput (read/write operations) is calculted in MB/s and can be compared in consistent and reliable manner between mobile and desktop platfotms and devices.

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

To be completed...
