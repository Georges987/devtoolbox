# Fluter installation tool

This Bash script automates the installation of flutter, a popular mobile developpement framework with dart, on a Debian or Ubuntu-based system. It updates the package lists, and install all necessary tool for flutter cli launching. Notice that it not install tool for lauchaing virtual devices.

## Usage

1. Open a terminal on your Debian or Ubuntu system.
2. Download the script or clone his repository from here.
3. Ensure that the script has execution permissions using the command chmod +x install.sh.
4. Execute the script using the following command:
   `sudo ./install.sh`

Follow the instructions displayed on the screen. The script install all requirements and add flutter to your bashrc file before source it. 
5. Valid flutter doctor with yes or o if you want to display the android tool required to launch flutter with android devices. 

## Notice
- The installation process requires an active internet connection.
- Make sure to run the script with superuser privileges (using sudo) to install and configure flutter on your debian / ubuntu system.
- After installation, you can access flutter cli. To create new app, run :
    - `flutter create <appname>`
    - `cd <appname> && flutter run`
 
### Disclaimer
**This script is provided as is, without any warranty. Use of this script is at your own risk.**
