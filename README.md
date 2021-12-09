# AR_Demo_RN

The repository for AR Demo React Native with Viro.

[![license](https://img.shields.io/badge/LICENSE-MIT-brightgreen)](https://opensource.org/licenses/mit-license.html) [![react-native](https://img.shields.io/badge/react--native-0.63.3-brightgreen)](https://facebook.github.io/react-native/docs/0.59/getting-started)

---

## Project Desctiption

ViroReact is an open-source development platform for rapidly building AR/VR applications using React Native. Use a single code base for your AR and VR apps.

## Prerequisites

**iOS** : XCode(12.0.1) onwards

**Android** : Android Studio(4.0) with gradle(6.3) onwards

**Editor** : Visual Studio Code

## How to Setup Project

**Step 1:** Clone this repository.

**Step 2:** Go to the cloned repo and open it in termianl.

**Step 3:** Install the dependencies with `$ yarn`

**Step 4:** Run the yarn script to install the cocoapods `$ yarn podinstall`

## How to Run the Project

1. Open the project directory in to terminal
2. Run and build for either OS
   _ Run iOS app
   `bash yarn ios`
   _ Run Android app
   `bash yarn android` \* Note: This npm scripts will lint your code first. If there are no lint errors, then it will run the ios or android app. Otherwise it will show the lint errors in the terminal.

## List of all dependencies used in the project with their usage

List all dependencies from the package.json file along with their usage. This list must be updated every time you change/add any dependecy. Here are some examples:

- **Framework:**
  - [React Native](https://github.com/facebook/react-native)

- **Libraries used for UI:**
  - [native-base](https://nativebase.io/),[@viro-community/react-viro](https://github.com/ViroCommunity/viro)
  
## Troubleshoot Notes

- There are no known issues for run or build processes right now.
