# Reserve

Reservation application develop for Coastal conservation & Resource Management Department in Sri Lanka

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

# Reserve
Reservation Application developing using react-native

### Used Expo
###### NativeWind for styling (Third party library that used to use Tailwind)
###### Icons -> Reactnative Heroicons
###### React natve navigation -> Rout between different screens
###### React native snap carousel -> This is slider (That we used to display all movies list)
###### Expo linear gradient - create beautyfull linear background
###### React native progress - Used to show loading screen (When fetching data from API)
###### Axios - Fetch API data

```
├── src
│   ├── api
│   │  ├── ApiCalls.js
│   │  ├── EndUrls.js
│   │  ├── index.js
│   ├── assets
│   │  ├── fonts
│   │  │  ├── font-name1.ttf
│   │  │  ├── font-name2.ttf
│   │  ├── images
│   │  │  ├── icon1.png
│   │  │  ├── icon2.png
│   ├── components
│   │  ├── common
│   │  │  ├── customButtonRN
│   │  │  │  ├── index.js
│   │  │  │  ├── styles.js
│   │  │  ├── customTextRN
│   │  │  │  ├── index.js
│   │  │  │  ├── styles.js
│   │  ├── presentation
│   │  │  ├── buttonRN
│   │  │  │  ├── index.js
│   │  │  │  ├── styles.js
│   │  │  ├── textRN
│   │  │  │  ├── index.js
│   │  │  │  ├── styles.js
│   ├── constants
│   │  │  ├── Enums.js
│   │  │  ├── Fonts.js
│   │  │  ├── Images.js
│   │  │  ├── ScreenNames.js
│   │  │  ├── StorageKeys.js
│   │  │  ├── Strings.js
│   │  │  ├── Colors.js
│   ├── hooks
│   │  │  ├── index.js
│   ├── navigation
│   │  │  ├── AppNavigator.js
│   │  │  ├── AuthNavigator.js
│   │  │  ├── TabNavigator.js
│   ├── redux
│   │  ├── actions
│   │  │  ├── Action1.js
│   │  │  ├── Action2.js
│   │  ├── constants
│   │  │  ├── Constants1.js
│   │  │  ├── Constants1.js
│   │  ├── reducers
│   │  │  ├── Reducer1.js
│   │  │  ├── Reducer2.js
│   │  ├── store.js
│   ├── screens
│   │  ├── homeScreen
│   │  │  ├── index.js
│   │  │  ├── styles.js
│   │  ├── aboutScreen
│   │  │  ├── index.js
│   │  │  ├── styles.js
│   ├── styles
│   │  ├── GlobalStyle.js
│   ├── utility
│   │  ├── index.js

```