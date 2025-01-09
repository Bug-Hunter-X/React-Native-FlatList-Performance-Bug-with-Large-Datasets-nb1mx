# React Native FlatList Performance Issue

This repository demonstrates a common performance problem encountered when using `FlatList` in React Native with extensive datasets.  The `renderItem` function is invoked excessively, leading to performance degradation and potential crashes.  The solution implemented optimizes rendering by using `keyExtractor` and potentially other techniques.

## Steps to Reproduce

1. Clone the repository.
2. Run `npm install` or `yarn install`.
3. Run the app on an emulator or device.
4. Observe the performance with a large data set.