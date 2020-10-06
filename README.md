# react-native-sounds-beep
A very lite module to play system sounds and beep for react-native apps (no sound files)

## Original Auther
Thanks to trietho

https://github.com/trietho/react-native-a-beep

## Install
using npm:
```js
npm i "react-native-sounds-beep"
```
or using yarn
```js
yarn add "react-native-sounds-beep"
```
## Usage

```js
import RNBeep from 'react-native-sounds-beep';
```
Examples:
```js
<Button onPress={ () => {RNBeep.beep()} } title="Beep Success"></Button>
<Button onPress={ () => {RNBeep.beep(false)} } title="Beep Fail"></Button>
<Button onPress={ () => {RNBeep.PlaySysSound(RNBeep.AndroidSoundIDs.TONE_CDMA_ABBR_ALERT)} } title="Beep Android Custom"></Button>
<Button onPress={ () => {RNBeep.PlaySysSound(41)} } title="Beep Something"></Button>
<Button onPress={ () => {RNBeep.PlaySysSound(RNBeep.iOSSoundIDs.AudioToneBusy)} } title="Beep iOS Custom"></Button>
```

Happy Beep!

FREE!