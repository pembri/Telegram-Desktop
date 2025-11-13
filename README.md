# Telegram-Desktop
Telegram application for Debian Linux distro
## How to install
First download the .deb file according to your device architecture, select arm64 or amd64 from [link here](https://github.com/pembri/Telegram-Desktop/releases)
#
continue by installing the chromium browse package with the command:
```
sudo apt update
sudo apt install chromium
```
After completing the installation of the chromium package, continue by installing the prepared .deb file, with the command:
```
sudo dpkg -i (downloaded_file.deb)
```
without sign (), as an example below
```
sudo dpkg -i telegram_linux_arm64_no-sandbox.deb
```
If it is installed, the Telegram application will automatically appear on the desktop homepage.
