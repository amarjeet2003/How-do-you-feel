# How do you feel Mobile App

This Project is built using Python and Kivy. 

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requirements.txt

```bash
pip install requirements.txt
```
For Creating an APK file out of .py file, you need to setup Ubuntu either on a VM or your main OS,
On your Ubuntu OS, run
```bash
# To Open the file contents
cat kivy-buildozer-installer.sh

# To Run the shell file
bash kivy-buildozer-installer.sh
```
Now Check whether the app is running on Ubuntu correctly
```bash
python3 main.py
```
For Making of APK file now,
```bash
# initializes buildozer library
buildozer init

# Creates APK file
buildozer android debug
```


## Usage
This mobile app displays quotes based upon the user's mood. It has Sign in/Up feature along with Login/Logout button.
