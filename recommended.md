# The Recommended 🔧
Here we will learn to install some languages and tools that are used in a majority of CSE courses.

## **gcc**, **gdb** & **valgrind** ⚔️
>Used in **COMP1511**, **COMP1521** & **COMP2521**
1. Install **gcc** & **gdb**
```
sudo apt install gcc
```
2. Confirm the installation of **gcc** & **gdb**
```
gcc --version
gdb --version
```
3. Install **valgrind** 
```
sudo apt install valgrind
```
4. Confirm the installation of **valgrind** 
```
valgrind --version
```
> ✨ **Bonus!** Install the [C/C++ Language Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools) VSCode extension for Intellisense features!
## **nodeJS** 🌐
>Used in **COMP1531** & **COMP6080**
1. Install **CURL** (a tool used for downloading content from the internet in the command-line) 
```
sudo apt-get install curl
```
2. Install **nvm** (*node version manager*)
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash
```
3. Confirm the installation of **nvm**. It should output `"nvm"` in the terminal. If you received `command not found`, start again from **Step 1**.
```
command -v nvm
```
4. Install **nodeJS**
```
nvm install --lts
nvm install node
```
5. Confirm the installation of **nodeJS**
```
node --version
npm --version
```

## **jdk** ☕
>Used in **COMP2511**
1. Install **jdk**
```
sudo apt install openjdk-11-jdk
```
2. Confirm the installation of **jdk**
```
java --version
```
> ✨ **Bonus!** Install the [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack) VSCode extension for Intellisense features!
## **python3** 🐍
>Used in **COMP1010**, **COMP2041** & **COMP3311**
1. Install **python3** & **pip3**
```
sudo apt install python3 python3-pip
```
2. Confirm the installation of **python3** and **pip3**
```
python3 --version
pip -V
```
> ✨ **Bonus!** Install the [Python Language Pack](https://marketplace.visualstudio.com/items?itemName=ms-python.python) VSCode extension for Intellisense features!
