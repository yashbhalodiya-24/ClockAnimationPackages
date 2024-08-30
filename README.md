# react-native-clock

This React Native Clock in add set time to yearly moring wakeup time to display and this clock is use expo app also.

## NPM Dependencies

This Dependencies Requried to use React Native Clock.

```jsx
npm i react-native-reanimated        -- save
```

---

```jsx
npm i react-native-redash            -- save
```

---


```jsx
npm i react-native-svg               -- save
```

---

```jsx
npm i react-native-gesture-handler   -- save
```

---


# Expo Dependencies

```jsx
npm i @expo/vector-icons             -- save
```

---

## Container Component Props

| parameter  | type   |  description |
| :--------  | :----  |  :---------- |
| start      | Animated.SharedValue<number> |  Represents the start angle in radians, typically indicating a specific time like erarly moring time.|
| end        | Animated.SharedValue<number>  |  Represents the end angle in radians, typically indicating a specific time like wake-up time.|
| children   |ReactNode| React children elements to be rendered inside the container, allowing for flexible component composition.|


## CircularSlider Component Props

| parameter  | type   |  description |
| :--------  | :----  |  :---------- |
| start      | Animated.SharedValue<number> |  Represents the start angle in radians, used to determine the initial position on the circular slider.|
| end        | Animated.SharedValue<number> |  Represents the end angle in radians, used to determine the final position on the circular slider.|
