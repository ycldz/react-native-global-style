
# React Native Global Style

The global style file allows you to write faster style codes in the react native project.


## Yol haritası

- Add the globalStyle.tsx file to the assets/css folder in the project

- Include it inside the page you want to use

  
## Kullanım/Örnekler

```javascript
  import { View, Text } from 'react-native';
  import { globalStyle as s } from '../assets/css/globalStyle';
  
  export default function Home() {
      return (
        <View style={[s.flex1, s.bgF5F5F9, s.aiC, s.jcC]}>
          <Text style={[s.fs19, s.fw600]}>Hellow World</Text>
        </View
      )
  }
```

  