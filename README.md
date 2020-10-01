
# react-native-speech-recognizer

## Getting started

`$ npm install react-native-speech-recognizer --save`

### Mostly automatic installation

`$ react-native link react-native-speech-recognizer`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-speech-recognizer` and add `RNSpeechRecognizer.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNSpeechRecognizer.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<
#### Window
1.create-react-native-app folder_name
2. cd folder_name yoou created 
3.npm start

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.mogulinker.speech.recognizer.RNSpeechRecognizerPackage;` to the imports at the top of the file
  - Add `new RNSpeechRecognizerPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-speech-recognizer'
  	project(':react-native-speech-recognizer').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-speech-recognizer/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-speech-recognizer')
  	```


## Usage
```javascript
import RNSpeechRecognizer from 'react-native-speech-recognizer';

// TODO: What to do with the module?
RNSpeechRecognizer;
```
  
