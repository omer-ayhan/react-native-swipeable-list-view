# react-native-swipeable-list-view(Refactored)
[![npm](https://img.shields.io/npm/v/react-native-swipeable-list-view?color=red&logo=npm)](https://www.npmjs.com/package/react-native-swipeable-list-view)
![Supports Android, iOS](https://img.shields.io/badge/platforms-android%20%7C%20ios-green.svg?color=skyblue&logo=react) 
![npm](https://img.shields.io/npm/dm/react-native-swipeable-list-view)


## Example:

![android](./screen-gif.gif) ![android](./screen-ios-gif.gif)



# Installation
**In order to use this package, you will also need to install *react-native-gesture-handler* to your project.**

# Properties

Prop | Default | Type | Description 
| :------------- |:---------------:| :---------------:| :-----|
 data | - | array |  objects to be passed into the renderItem and renderHiddenItem functions **(is Required)**. |
 renderRightItem | - | function | 	How to render a row. Should return a valid React Element **(is Required)**. |
 renderHiddenItem | - | function | How to render a hidden row in a List (renders behind the row). Should return a valid React Element **(is Required)**. |
rightOpenValue | 200 | number | TranslateX value for opening the row to the right (positive number) **(is Required)**. |
 onSwipelistOpen | - | function | Called when row gets open. |
 onSwipelistClose | - | function | Called when row is closed. |
 overshootRight | false | boolean | a boolean value indicating if the swipeable row can be pulled further than the right actions row width. |
 friction | 1 | number | a number that specifies how much the visual interaction will be delayed compared to the gesture distance. e.g. value of 1 will indicate that the swipeable panel should exactly follow the gesture, 2 means it is going to be two times "slower". |


