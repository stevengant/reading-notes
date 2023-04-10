# Reading Class 41

## getting started with react native

[React Native - Core Components](https://reactnative.dev/docs/intro-react-native-components)
1. Name three Core Components of React Native and describe what they do.
  - `<View>`: A container that supports layout with flexbox, style, touch handling and accessibility controls
  - `<Text>`: Displays, styles, nests strings of text and handles touch events
  - `<Image>`: Displays different types of images

2. What problem does React Native solve (why call it native)?
  - Allows for cross platform programming (iOS and Android primarily)

3. What are the building blocks of a React Native app? How does that compare to a React app?
  - Views: Can be used to display text, images and respond to touch input

## expo

  [Expo](https://expo.dev/)
1. What solution does expo provide?
  - Expo is a set of tools and services that make it easier to develop and deploy React Native applications

2. Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.
  - bare

3. What is the difference between React Native and Expo?
  - React Native is a framework and Expo is a set of tools built on top of React Native that make it easier to develop, test and deploy mobile apps

## expo snack

[Expo Snack](https://snack.expo.dev/)
1. Checkout this tool. What does snack allow you to do?
  - Allows you to write code and run/test it - similar to ReplIt

## ejecting

[Expo Eject](https://docs.expo.dev/archive/glossary/#eject?redirected)
1. What does “eject” mean within the context of Expo?
When should you not eject?
  - Eject allows you to leave Expo dev environment
    - If your app does not require custom native code
    - If you want to take advantage of Expo's benefit
    - If you're a beginner
    - If you don't need increased perfomance

2. Why might you choose to eject?
  - If your app requires custom native code
  - Advanced configuration
  - Dependency management
  - Performance