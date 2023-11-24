# Dynamic Icon - Android App

## Overview

This Android project demonstrates a method to dynamically change app icons at runtime, providing users with a more personalized experience. The solution involves utilizing activity-alias in the app's manifest file and leveraging the PackageManager class to switch between different icons seamlessly.

![Sample GIF](https://github.com/oguzhanaslann/DynamicIcon/blob/master/sample/sample.gif)


## Implementation Details

The core implementation revolves around using activity-alias in the manifest file to define alternate activities with distinct icons. The key steps include:

1. **Manifest Setup:** Define the main activity and an activity alias with different icons.

2. **PackageManager Usage:** Utilize the PackageManager class to enable/disable activity aliases, effectively changing the app's icon at runtime.

3. **Code Refactoring:** Enhance code cleanliness by abstracting component names and leveraging BuildConfig and manifest placeholders for flexibility.

## Project Structure

### Code Components
- **MainActivity:** Contains the core logic to switch between activity-aliases for icon changes.
- **Utility Functions:** The `changeEnabledComponent` function provides a clean way to toggle activity-aliases.

### Resources
- **Manifest File:** Demonstrates the use of activity-alias and manifest placeholders.
- **Build.gradle:** Utilizes BuildConfig and manifest placeholders for dynamic component names.

### Additional Notes
- The project contains a sample user interface to demonstrate the icon change functionality interactively.

## How to Use

1. Clone or download the project.
2. Import it into Android Studio or your preferred IDE.
3. Run the app on an Android device or emulator.
4. Click designated UI elements to trigger icon changes using the implemented method.

## Contributions

Contributions to enhance the project or extend its functionality are welcome! Feel free to fork this repository, make changes, and create pull requests.

## References

- [GeeksforGeeks - Programmatically Change App Icon in Android](https://www.geeksforgeeks.org/how-to-change-app-icon-of-android-programmatically-in-android/)
- [Official Android Developer Guide - Activity Alias Element](https://developer.android.com/guide/topics/manifest/activity-alias-element)

## Main Article
- [Article Link: Dynamically Changing Android App Icons](https://medium.com/p/a61f8570ab9f)







