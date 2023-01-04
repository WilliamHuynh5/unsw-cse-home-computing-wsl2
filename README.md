# Home Computing at CSE using WSL2

Work seamlessly on a Linux environment without having to deal with the pain and suffering that is VLAB or SSH!

## Why WSL2 ? 🤔
You have probably used **TigerVNC** or **SSH** to connect to UNSW's CSE machines before, allowing you to edit your files or execute terminal commands on CSE servers. 

However the **TigerVNC/SSH** experience is not exactly smooth, with numerous issues such as timeouts, disk quota limits, port numbers being stolen, or general unresponsiveness just to name a few.

The solution this guide will go through will provide a method of working locally, creating a setup where we can use a lot of the Linux commands and scripts that are taught in a majority of CSE courses, whilst also avoiding the above issues too!

## What is WSL ? 🧠

**Windows Subsystem for Linux** (WSL) can be used to run a wide variety of Linux software, including shells, text editors, and programming languages, on a Windows machine. 

It is useful for developers who want to run Linux tools on their Windows machine, but prefer the convenience of a Windows environment.

## Preface 🐶

There are two versions of WSL, that being **WSL** & **WSL2**.

This guide will demonstrate the **installation of WSL2**, as it offers both faster performance and is considered the successor to **WSL**. A detailed comparison between both versions can be found [here](https://learn.microsoft.com/en-us/windows/wsl/compare-versions#comparing-features).

## Getting Started 🎉

First off, we need to check our Windows build! If you are on `build 19041` or later, you can install **WSL2** with a single command! 

If you are on an older version, there are a few extra steps, but it is still simple all the same!

>You can check your Windows build by opening Search and entering `winver`.

![Windows Version Example](/assets/img1.png "img1")

>You can update your version of Windows [here](https://support.microsoft.com/en-au/topic/windows-10-update-assistant-3550dfb2-a015-7765-12ea-fba2ac36fb3f).


## Installing WSL on Build 19041+ 

1. Open **Start** on Windows
2. Search for **Command Prompt**
3. Right-click the top result, and select **Run as administrator** from the menu
4. Type the following command and press **Enter**:
```
wsl --install
```
5. And voila! To confirm your installation, you can type the following command and press **Enter**:
```
wsl -l -v
```

## Installing WSL on older builds
Please follow this guide [here](https://learn.microsoft.com/en-au/windows/wsl/install-manual).







