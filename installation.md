# Installing WSL2

## Preface 🐶

There are two versions of WSL, that being **WSL** & **WSL2**.

This guide will demonstrate the **installation of WSL2**, as it offers both faster performance and is considered the successor to **WSL**. A detailed comparison between both versions can be found [here](https://learn.microsoft.com/en-us/windows/wsl/compare-versions#comparing-features).

## Getting Started 🎉

First off, we need to check our Windows build! If you are on `build 19041` or later, you can install **WSL2** with a single command! 

If you are on an older version, there are a few extra steps, but it is still simple all the same!

>You can check your Windows build by opening Search and entering `winver`.

![Windows Version Example](/assets/img1.png "img1")

>You can update your version of Windows [here](https://support.microsoft.com/en-au/topic/windows-10-update-assistant-3550dfb2-a015-7765-12ea-fba2ac36fb3f).


## Installing WSL on Build 19041+ 🛠️

1. Open **Start** on Windows
2. Search for **Command Prompt**
3. Right-click the top result, and select **Run as administrator** from the menu
4. Type the following command and press **Enter**:
```
wsl --install
```
5. And voila! You can confirm your installation, by typing the following command and pressing **Enter**:
```
wsl -l -v
```

## Installing WSL on older builds 👴
Please follow this guide [here](https://learn.microsoft.com/en-au/windows/wsl/install-manual).

## Post Installation 🙌
You can launch **WSL2** by opening **Start** on Windows and searching for **Ubuntu**.
> **Ubuntu** is the default linux distribution installed by WSL2. It is very beginner friendly to use and has a lot of documentation + support online. You can check it out [here](https://learn.microsoft.com/en-us/windows/wsl/)!

✅ Now it's time to configure our **WSL2** setup! 😎 To get started, click [here](configure.md)!



