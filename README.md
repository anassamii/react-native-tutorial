npm install
upgrade the expo sdk
changes in node_modules/metro-config/src/default/blacklist.js
clear cache: expo start -c / yarn start --reset-cache ? / npm start --reset-cache ?
changes on App.js: import AppLoading from 'expo-app-loading'; rather than import { AppLoading } from 'expo';
changes on node_modules/react-navigation-drawer/.../views/drawer.js:  interpolateNode rather than interpolate
Add this line in the babel.config.js file : plugins: ['react-native-reanimated/plugin'],
other installations ?
expo start / npm start

# react-native-tutorial
All the course files for the React Tutorial for Beginners playlist on The Ne Ninja Playlist
