
# react-native-intent

## Getting started

`$ npm install react-native-intent --save`

### Mostly automatic installation

`$ react-native link react-native-intent`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-intent` and add `RNIntent.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNIntent.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.github.raininfall.react.native.intent.RNIntentPackage;` to the imports at the top of the file
  - Add `new RNIntentPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-intent'
  	project(':react-native-intent').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-intent/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-intent')
  	```


## Usage
```javascript
import RNIntent from 'react-native-intent';

// TODO: What to do with the module?
RNIntent;
```
  