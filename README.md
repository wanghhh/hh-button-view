
# react-native-hh-button-view

## Getting started

`$ npm install react-native-hh-button-view --save`

### Mostly automatic installation

`$ react-native link react-native-hh-button-view`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-hh-button-view` and add `RNHhButtonView.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNHhButtonView.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.onepice.buttonview.RNHhButtonViewPackage;` to the imports at the top of the file
  - Add `new RNHhButtonViewPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-hh-button-view'
  	project(':react-native-hh-button-view').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-hh-button-view/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-hh-button-view')
  	```


## Usage
```javascript
import RNHhButtonView from 'react-native-hh-button-view';

// TODO: What to do with the module?
RNHhButtonView;
```
  