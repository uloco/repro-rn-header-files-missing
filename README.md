# Repro Missing Header Files

This was is bootstrapped with `npx react-native init RN68new --version 0.68.2`

See Issue: https://github.com/facebook/react-native/issues/33692


### Instructions

1. Run `npm install`
2. Run `npx pod-install`
3. Run `ls -al ios/Pods/Headers/Yoga/yoga`
4. See missing headers like `BinUtils.h` etc. (They are located at `node_modules/ReactCommon/yoga/yoga/` and all of them should be linked here)
5. Try to build xcode build and see missing header error. 

