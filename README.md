#Dribbble React-Native (React Redux example)

This project tries to use the React-native to build a
Dribbble App. And it contains shots page, user page,
shot detail page.

We try to use the modern [redux](https://github.com/reactjs/redux) way to handle the state change.

## ScreenShots
![iOS](https://raw.githubusercontent.com/gongmingqm10/Dribbble-ReactNative/master/arts/iOS.png)

## Libraries we used
```
  "dependencies": {
    "react": "^15.1.0",
    "react-native": "0.27.2",
    "react-native-htmlview": "^0.5.0",
    "react-native-router-flux": "^3.30.2",
    "react-native-vector-icons": "^2.0.3",
    "redux": "^3.5.2",
    "redux-thunk": "^2.1.0"
  }
```

## How to run

Basically this should be working on both Android & iOS platforms. Make sure
you have install XCode correctly when you want to run iOS version. Android version
is still be continuous migrating, but should works fine soon.

Launch the iOS version:

```
$: cd Dribbble-ReactNative
$: npm install
$: react-native run-ios
```

If you want to launch Android version: please run `react-native run-android`

## Platforms we need to support

Both Android and iOS should be supported

## TODO

1. ~~[iOS] Fix the Navigator padding top issues.~~
2. ~~[Android] Add the DrawerMenu View to contains Components~~
3. ~~[Android] Shots page compatibility~~
4. ~~[Android] User page compatibility~~
5. ~~[Android] Shot detail page compatibility~~
6. ~~[Android] Rounded Image is not working~~
7. [App] Add initial tests especially for reducers test
8. [CI] Add auto deploy script to assemble Android & iOS package

## LICENSE
```
The MIT License (MIT)

Copyright (c) 2016 Ming Gong

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```



