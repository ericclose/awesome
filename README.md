# awesome

## Android

### General

* [ADB](https://developer.android.com/studio/releases/platform-tools#downloads)

<details><summary>Details</summary>

> Android SDK Platform-Tools is a component for the Android SDK. It includes tools that interface with the Android platform, primarily [`adb`](https://developer.android.com/studio/command-line/adb) and [`fastboot`](https://android.googlesource.com/platform/system/core/+/master/fastboot/#fastboot).

</details>

* [copy-partitions-20220613-signed.zip](https://mirrorbits.lineageos.org/tools/copy-partitions-20220613-signed.zip)

<details><summary>Details</summary>

> **Ensuring all firmware partitions are consistent**
>
> NOTE: The steps below only need to be run once per device.
>
> In some cases, the inactive slot can be unpopulated or contain much older firmware than the active slot, leading to various issues including a potential hard-brick. We can ensure none of that will happen by copying the contents of the active slot to the inactive slot.

</details>

* [MindTheGapps](https://androidfilehost.com/?w=files&flid=322935)

<details><summary>Details</summary>

> Google apps are the proprietary Google-branded applications that come pre-installed with most Android devices, such as the Play Store, Gmail, Maps, etc. Due to licensing restrictions, these apps cannot come pre-installed with LineageOS and must be installed separately. The Google apps are not required to boot or run LineageOS, however many users find them beneficial to take full advantage of the Android ecosystem.
> 
> These apps have been packaged by developers independent of LineageOS, and download links have been provided for your convenience only. It is possible to perform a “backup” of the Google apps on your device and then “restore” them, but this does take additional steps which are not covered here.
>
> The Google apps packages are **not supported** in any way by LineageOS.
>
> source: [Google apps - LineageOS Wiki](https://wiki.lineageos.org/gapps)

</details>

* [Magisk](https://github.com/topjohnwu/Magisk/releases/latest)

<details><summary>Details</summary>

> Magisk is a suite of open source software for customizing Android, supporting devices higher than Android 5.0.
Some highlight features:
>
> * MagiskSU: Provide root access for applications
> * Magisk Modules: Modify read-only partitions by installing modules
> * MagiskBoot: The most complete tool for unpacking and repacking Android boot images
> * Zygisk: Run code in every Android applications' processes

</details>

* [payload-dumper-go](https://github.com/ssut/payload-dumper-go/releases/latest)

<details><summary>Details</summary>

> An android OTA payload dumper written in Go.

</details>

### Motorola-specific

* [motorola_flash_xml](https://gitlab.com/ThomasHastings/motorola_flash_xml)

<details><summary>Details</summary>

> This is a tool that creates a fastboot script from a Motorola servicefile.xml file.
The original idea comes from [RootJunky on GitHub](https://github.com/rootjunky/Motorola-XML-To-Batch-Script), but it seemed not to work for my Edge 20 Pro. The fastboot-related files are taken from that repo.

</details>
