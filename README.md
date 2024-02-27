This is a To Do List App, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# Getting Started

## System Requirements

 * Windows 11
 * NodeJS v18.16.0
 * NPM v9.8.1
 * Android Studio v2022.3.1

## Setup Instructions

### NodeJS and NPM

1. Download and install NodeJS (LTS version) from https://nodejs.org/en.
   * Leave the options checked in the options screen.
   * Download the additional libraries using Chocolatey when prompted.
   
2. Enter the following in the command line to update the NPM (Node Package Manager):

   ```bash
   npm install -g npm
   ```

### Yarn

1. Install the Yarn package manager with the following commands:

   ```bash
   corepack enable
   corepack prepare yarn@stable --activate
   ```

### Android Studio

1. Download and run the Android Studio installer from https://developer.android.com/studio.
2. Follow the installation wizard and ensure the "Android Studio" and "Android Virtual Device" components are selected.
3. Once Android Studio is installed, launch it.
4. Complete the initial setup, including installing the Android SDK and setting up an Android Virtual Device (AVD) emulator.

### Environment Variables

1. Search for "Environment Variables" in the Windows search bar
2. Click "Edit the system environment variables," and then click "Environment Variables.
3. Under "System variables," find the "Path" variable, select it, and click "Edit."
4. Add the following paths and then click "OK":
   * ``%LOCALAPPDATA%\Android\Sdk``
   * ``%LOCALAPPDATA%\Android\Sdk\platform-tools``

## Start App

1. Open the command line in the same directory as this project.
   * Open the folder in Windows Explorer and enter "cmd" in the address bar.
2. Install the associated packages for the app with the following command:
   ```bash
   yarn install
   ```
3. Start the app with the following command:
   ```bash
   yarn run start
   ```

# Troubleshooting

 * The PATH variable needs to have the paths for the Android SDK and Platform Tools in order for the app to start.
 * The React Native CLI is more compatible with the Yarn package manager.
 * NodeJS needs to be up to date.