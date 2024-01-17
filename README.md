# Flutter_Hero

![Flutter Logo](https://github.com/Asifekhlaque/Flutter_Hero/assets/132199879/4362aa26-7f25-4a90-a254-c92703b6ac01)
# Day-01
## What is Flutter?

Flutter is a framework for building mobile and web applications with a single codebase, simplifying cross-platform app development.

## Native vs Cross-platform vs Hybrid

- **Native:**
  - Built for one platform (iOS/Android) with platform-specific languages.
  - Example: Swift/Obj-C for iOS, Java/Kotlin for Android.
  - Pros: Optimal performance, native look.
  - Cons: Separate codebases.

- **Cross-platform:**
  - Develops for multiple platforms using frameworks like Flutter or React Native.
  - Example: Flutter (Dart), React Native (JavaScript).
  - Pros: Single codebase, faster development.
  - Cons: Slightly lower performance.

- **Hybrid:**
  - Combines web tech with native elements.
  - Example: Ionic (HTML, CSS, JS), Apache Cordova.
  - Pros: Single codebase, web technologies.
  - Cons: Performance may lag, relies on WebView.

## Benefits of Flutter

1. **Single Codebase:**
   - Write once, deploy on iOS, and Android, saving time.

2. **Hot Reload:**
   - See instant changes, speeding up development.

3. **Rich UI:**
   - Customizable, visually appealing interfaces with pre-designed widgets.

4. **Performance:**
   - Dart compiles to native code, ensuring high performance.

5. **Community Support:**
   - Active community, plugins, and support.

6. **Open Source:**
   - Freedom to contribute and customize.

7. **Adaptability:**
   - Build for mobile, web, and desktop from one codebase.

8. **Consistent Design:**
   - Unified UI across platforms.

9. **Growing Ecosystem:**
   - Expanding plugins and packages for integration.

10. **Google Backing:**
    - Developed and maintained by Google, ensuring updates.
### Flutter Architecture
![image](https://github.com/Asifekhlaque/Flutter_Hero/assets/132199879/91bcafaf-625a-48c2-a5a5-e0d6bcf5568a)

1. **Widgets:**
   - Fundamental UI elements, shaping the app's structure and appearance.

2. **Element Tree:**
   - Flutter's hierarchy of widgets, forming a visual representation of the app's UI.

3. **Render Tree:**
   - Transforms the element tree into a visual layout with graphics, creating the app's actual appearance.

4. **Flutter Engine:**
   - Low-level rendering engine bridging Flutter with the underlying platform (iOS/Android).

5. **Dart Framework:**
   - Core functionality and logic coded in Dart, serving as the foundation for Flutter apps.

6. **Hot Reload:**
   - Enables instant viewing of code changes without app restart, facilitating rapid development.

7. **Material Design and Cupertino Widgets:**
   - Widgets adhering to design principles (Material for Android, Cupertino for iOS), ensuring a native feel.

8. **Plugins:**
   - Extends Flutter's capabilities by integrating native code, enhancing app features.

9. **State Management:**
   - Employs various approaches (Provider, Riverpod, Bloc) to handle app state and data flow.

10. **Platform Channels:**
    - Facilitates communication between Dart and native code, enabling interaction with device-specific features and APIs.
# Day-02
## Flutter Installation

1. **Check Flutter Installation:**
   - Press `Windows + R`, type `CMD`, and press enter.
   - Type `flutter` in the command prompt.
   - If nothing is shown, Flutter is not installed.

2. **Download Flutter SDK:**
   - Visit [Flutter Downloads](https://flutter.dev/docs/get-started/install) using Chrome.
   - Download the latest Flutter SDK for Windows.

3. **Install Android Studio:**
   - Download and install the latest version of [Android Studio](https://developer.android.com/studio).
   - Note: Ensure compatibility with your Flutter version.

4. **SDK Manager Settings:**
   - Open Android Studio.
   - In 'More Settings', locate 'SDK Manager'.
   - Navigate to 'SDK Settings' and download 'SDK Command Line' (second option).

5. **Configure Flutter:**
   - Open a command prompt.
   - Run `flutter doctor` to check requirements.
   - Resolve any missing dependencies reported by Flutter Doctor.

6. **Ready for Flutter Development:**
   - Once all requirements are satisfied, you are ready for Flutter development.
![image](https://github.com/Asifekhlaque/Flutter_Hero/assets/132199879/23bc7fac-f0dd-4b17-907e-c062205d3523)

# Day-03
### Project Structure Overview
![image](https://github.com/Asifekhlaque/Flutter_Hero/assets/132199879/49d44fb5-85c7-4c3c-8967-7f51692be963)

```
📁 my_flutter_project
  |
  ├─ 📁 android           # Android-specific files and configurations
  |   ├─ ...
  |
  ├─ 📁 assets            # Static assets like images, fonts, etc.
  |   ├─ ...
  |
  ├─ 📁 ios               # iOS-specific files and configurations
  |   ├─ ...
  |
  ├─ 📁 lib               # Dart code for the Flutter application
  |   ├─ 📁 screens       # UI screens or pages
  |   |   ├─ home.dart
  |   |   ├─ profile.dart
  |   |   └─ ...
  |   |
  |   ├─ 📁 widgets       # Reusable widgets
  |   |   ├─ button.dart
  |   |   ├─ card.dart
  |   |   └─ ...
  |   |
  |   ├─ main.dart        # Entry point of the application
  |   └─ ...
  |
  ├─ 📁 test              # Unit and widget tests
  |   ├─ ...
  |
  ├─ 📄 .gitignore        # Git ignore file
  ├─ 📄 pubspec.yaml      # Flutter dependencies and project metadata
  └─ ...
```

### Folder Descriptions

- **android:** Contains Android-specific configurations and files.

- **assets:** Holds static assets like images, fonts, and other resources.

- **ios:** Includes iOS-specific configurations and files.

- **lib:** Main Dart code for the Flutter application.
  - **screens:** UI screens or pages.
  - **widgets:** Reusable widgets.

- **test:** Houses unit and widget tests.

- **.gitignore:** Specifies files and directories to be ignored by version control.

- **pubspec.yaml:** Declares dependencies and project metadata.
