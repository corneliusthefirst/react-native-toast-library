
# react-native-native-toast-library-rc

## Getting started

`$ npm install react-native-native-toast-library-rc --save`

### Mostly automatic installation

`$ react-native link react-native-native-toast-library-rc`

### Manual installation

#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-native-toast-library-rc` and add `RNNativeToastLibrary.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNNativeToastLibrary.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`

- Add `import com.reactlibrary.RNNativeToastLibraryPackage;` to the imports at the top of the file
- Add `new RNNativeToastLibraryPackage()` to the list returned by the `getPackages()` method

2. Append the following lines to `android/settings.gradle`:

   ```
   include ':react-native-native-toast-library-rc'
   project(':react-native-native-toast-library-rc').projectDir = new File(rootProject.projectDir,  '../node_modules/react-native-native-toast-library-rc/android')
   ```

3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:

   ```
      compile project(':react-native-native-toast-library-rc')
   ```

#### Windows

[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNNativeToastLibrary.sln` in `node_modules/react-native-native-toast-library-rc/windows/RNNativeToastLibrary.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app

- Add `using Native.Toast.Library.RNNativeToastLibrary;` to the usings at the top of the file
- Add `new RNNativeToastLibraryPackage()` to the `List<IReactPackage>` returned by the `Packages` method

## Usage

```javascript
import RNNativeToastLibrary from 'react-native-native-toast-library-rc';

// TODO: What to do with the module?
RNNativeToastLibrary;
```
  