# react-native-smart-karrot

## Getting started

`$ npm install react-native-smart-karrot --save`

### Mostly automatic installation

`$ react-native link react-native-smart-karrot`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-smart-karrot` and add `SmartKarrot.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libSmartKarrot.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.SmartKarrotPackage;` to the imports at the top of the file
  - Add `new SmartKarrotPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-smart-karrot'
  	project(':react-native-smart-karrot').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-smart-karrot/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-smart-karrot')
  	```


## Usage
```javascript
import SmartKarrot from 'react-native-smart-karrot';

// TODO: What to do with the module?
SmartKarrot;
```
