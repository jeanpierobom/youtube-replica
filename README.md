# youtube-replica
This is an app I am building to learn React Native

## Running this prototype
The instructions for running this prototype are:

1) Clone the repository in your computer with the following command:
```console
git clone https://github.com/jeanpierobom/youtube-replica.git
```
2) Install all necessary dependencies by typing:
```console
npm install
```
3) Start the Android Emulator. In order to do this, go to Tools / AVD Manager in your Android Studio. If you already have a Virtual Device, just click the play button to run it. Otherwise, you will need to install a new Virtual Device by clicking on the "Create Virtual Device", selecting a device definition and downloading a system image of your choice. All this process can be done by following a wizard.
4) Next, you will need to export a system variable 
```console
export ANDROID_HOME=/Applications/ADT/sdk
```
Replace "/Applications/ADT/sdk" by whatever is the installation path in your computer.
5) Run the application by typing the following command in the terminal:
```console
react-native run-android
```
