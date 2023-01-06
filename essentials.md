# The Essentials 🔧
Here we will learn how to setup VSCode and Git with WSL, which are the bare necessities to get us programming!

## Installing VSCode & the WSL extension 💻
1. Visit the [VSCode install page](https://code.visualstudio.com/download) and download & run the installer.
2. Install the [Remote Development extension pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack).
3. And that's all! To run it, simply open **Ubuntu**, and in the terminal, enter this command:
```
code
```
![Code Example](/assets/gif1.gif "gif1")

> To open a specific file in VSCode, you can run: `code myfile.txt`

> To open your current working directory in VSCode, you can run: `code .`

## Installing Git 🏕️
1. Open **Ubuntu**, and in the terminal, enter this command:
```
sudo apt-get install git
```
2. Adding your name to Git. This could be your **UNSW username** (i.e. *ashesh.mahidadia420*) or your **GitHub** username.
```
git config --global user.name "Your Name"
```
3. Adding your email address  to Git. This could be your **UNSW email address** or your own email address.
```
git config --global user.email "youremail@domain.com"
```

## Using SSH keypairs to work on GitHub & GitLab 🔑 
1. We will generate a new SSH key. Open **Ubuntu**, and in the terminal, enter this command. For each question, just hit the Enter key.
```
ssh-keygen
```
```
$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/import/kamen/3/z5555555/.ssh/id_rsa):
Created directory '/import/kamen/3/z5555555/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /import/kamen/3/z5555555/.ssh/id_rsa.
Your public key has been saved in /import/kamen/3/z5555555/.ssh/id_rsa.pub.
The key fingerprint is:
b8:02:31:8b:bf:f5:56:fa:b0:1c:36:89:ad:e1:cb:ad z5555555@williams
The key's randomart image is:
```

2. Now we want to view and copy the SSH key to our clipboard. To view the SSH key, Enter the following command. After that copy its contents using `ctrl+c`. 
```
cat ~/.ssh/id_rsa.pub
```

3. Navigate to https://gitlab.cse.unsw.edu.au/-/profile/keys, and enter in your SSH key.

![Code Example](/assets/img5.png "img5")

> If you don't have a GitHub account, you can skip this step!
4. Navigate to https://github.com/settings/ssh/new, and enter in your SSH key.


![Code Example](/assets/img6.png "img6")

### ✅ Now it's time to install the recommended! 😎 To get started, click [here](recommended.md)!
