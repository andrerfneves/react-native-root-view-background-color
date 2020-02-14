# react-native-root-view-background-color

## Getting started

#### RN >= 0.60

If you are using RN >= 0.60, only run `pod install` from the ios directory. Then rebuild your project.

#### RN < 0.60

For RN < 0.60, you need to link the dependency using `react-native link`:

```bash
react-native link react-native-root-view-background-color
```

Then run `pod install` from the ios directory and rebuild your project.


## Usage
```javascript
import RootViewBackgroundColor from 'react-native-root-view-background-color';


// Set the Root View background color to black
RootViewBackgroundColor.setBackground(0, 0, 0, 1);

// Set the Root View background color to white
RootViewBackgroundColor.setBackground(255, 255, 255, 1);
```

_**Note:**_ Requires `minSdkVersion = 21` or newer. 
