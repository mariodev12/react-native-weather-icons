# React Native Weather Icons

![alt text](https://camo.githubusercontent.com/0cc2a70059ed45e7eb0e845aa576e12eeefb9b93/687474703a2f2f692e696d6775722e636f6d2f586d5a573271332e706e67)

After searching for weather icons, I found a great font called [Weather Icons]( https://github.com/erikflowers/weather-icons) but the problem was that I couldn't use it with React Native. Then the solution was install the component [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons) and create a custom font with [Weather Icons]( https://github.com/erikflowers/weather-icons).

You have to install [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons) first.

### How to install Weather Icons

 - git clone https://github.com/mariodev12/react-native-weather-icons.git
 - create a folder inside your project and put inside selection.json and weatherIcon files
 - open your app on Xcode and add manualy icomoon.ttf font.
 - Inside your project import weatherIcon.js where you need to add a Icon.
 - Use it like this <Icon name="wi-day-sunny" />

### Troubleshoot

If you have errors like unrecognized font family can be fixed with the following:

- Shutdown your react native app and restart it.
- Open Xcode and go to Product->Clean Build Folder and Build
- Check if inside info.plist, fonts provided by application is icomoon.ttf referenced
- Use react-native link again.
