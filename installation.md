# Installing WSL2

## Preface 🐶

There are two versions of WSL, that being **WSL** & **WSL2**.

This guide will demonstrate the **installation of WSL2**, as it offers both faster performance and is considered the successor to **WSL**. A detailed comparison between both versions can be found [here](https://learn.microsoft.com/en-us/windows/wsl/compare-versions).


## Getting Started 🎉

First off, we need to check our Windows build! If you are on **`build 19041`** or later, you can install **WSL2** with a **single command**! 

If you are on an older version, there are a few extra steps, but it is still simple all the same!

>You can check your Windows build by opening **Start** and entering `winver`. 🤔

![Winver Example](/assets/img2.png "img2")

As you can see below, my Windows build is **`build 22000`** which is later than **`build 19041`**. This means I can install **WSL2** with a single command!

![Windows Version Example](/assets/img1.png "img1")

>If needed, you can update your build of Windows [here](https://support.microsoft.com/en-au/topic/windows-10-update-assistant-3550dfb2-a015-7765-12ea-fba2ac36fb3f).

## Installing WSL on Build 19041+ 🛠️

1. Open **Start** on Windows
2. Search for **Command Prompt**
3. Right-click the top result, and select **Run as administrator** from the menu
4. Type the following command and press **Enter**:
```
wsl --install
```
5. Wait for the installation to complete, and voila! You can confirm your installation, by typing the following command and pressing **Enter**:
```
wsl -l -v
```

> If your installation was unsuccessful for any reason, try it again from the first step 😄

## Installing WSL on older builds 👴
Please follow this guide [here](https://learn.microsoft.com/en-au/windows/wsl/install-manual).

## Post Installation 🙌
You can launch **WSL2** by opening **Start** on Windows and searching for **Ubuntu**.
> **Ubuntu** is the default linux distribution installed by WSL2. It is very beginner friendly to use and has a lot of documentation + support online. You can check out the documentation [here](https://learn.microsoft.com/en-us/windows/wsl/)!

> **Important!** When you launch WSL2 for the first time, you will be prompted to enter a password. But the password characters are invisible! This is known as blind typing. If you accidentally typed something and don't remember what it was, just hold the backspace key for a good five seconds 😅. Then carefully type in your password again, and press Enter!

![Ubuntu Example](/assets/img3.png "img3")

### ✅ Now it's time to configure our **WSL2** setup! 😎 To get started, click [here](configure.md)!



