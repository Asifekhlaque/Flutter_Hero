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

# Day-04
**Benefits of Dart Language:**

1. **Simplicity:** Dart is designed with simplicity in mind, making it easy to learn and understand for developers.

2. **Strong Typing:** Dart is statically typed, which helps catch errors during development, providing better code reliability.

3. **Object-Oriented:** Dart follows object-oriented principles, promoting code organization and reuse.

4. **Cross-Platform Development:** Dart is the primary language for developing Flutter apps, allowing for cross-platform development with a single codebase.

5. **Hot Reload:** Dart's hot reload feature in Flutter facilitates faster development by quickly applying code changes without restarting the entire application.

6. **Rich Standard Library:** Dart comes with a comprehensive standard library, providing a wide range of functionalities for developers.

7. **Asynchronous Programming:** Dart supports asynchronous programming, making it suitable for building scalable and responsive applications.

8. **Community Support:** With a growing community, Dart benefits from an active ecosystem, including libraries, tools, and documentation.
# First Dart Program
```dart
import 'dart:io';
void main(){
  print("First Dart Program");
  stdout.write("What is your name?\n");
  String? name = stdin.readLineSync();
  print(name);
}
```
# Day-05
# Class object in Dart
![code](https://github.com/Asifekhlaque/Flutter_Hero/assets/132199879/fb03ff41-c93b-4c6a-a787-46f41b953aed)
# Variable and Data type
```dart
void main(){
  int a;//None nullable variable
  int? b;//Nullable variable
  print(a);// It will give error
  print(b);//It will print null
}
```

### Dart Data Types

1. **int**: Stands for integer. It represents whole numbers.

   ```dart
   int age = 25;
   ```

2. **double**: Stands for double-precision floating-point. It represents decimal numbers.

   ```dart
   double price = 49.99;
   ```

3. **String**: Represents a sequence of characters, like text.

   ```dart
   String name = "John Doe";
   ```

4. **bool**: Stands for boolean. It represents either `true` or `false`.

   ```dart
   bool isAdult = true;
   ```

5. **List**: Represents an ordered collection of items.

   ```dart
   List<String> fruits = ["Apple", "Banana", "Orange"];
   ```

6. **Map**: Represents a collection of key-value pairs.

   ```dart
   Map<String, dynamic> person = {
     "name": "Alice",
     "age": 30,
     "isStudent": false,
   };
   ```

7. **dynamic**: Represents a variable that can hold any type of value.

   ```dart
   dynamic dynamicVariable = 42;
   dynamicVariable = "Hello, Dart!";
   ```

### Example Usage in Dart Code

```dart
void main() {
  // Variables with different data types
  int age = 25;
  double height = 5.9;
  String name = "John Doe";
  bool isStudent = true;
  List<String> hobbies = ["Reading", "Traveling", "Coding"];
  Map<String, dynamic> person = {
    "name": "Alice",
    "age": 30,
    "isStudent": false,
  };
  dynamic dynamicVariable = 42;

  // Print values
  print("Name: $name");
  print("Age: $age");
  print("Height: $height");
  print("Is a student? $isStudent");
  print("Hobbies: $hobbies");
  print("Person: $person");
  print("Dynamic Variable: $dynamicVariable");
}
```


### `var`:

- **Usage:** `var variableName = value;`
- **Meaning:** The `var` keyword allows Dart to infer the type of the variable based on the assigned value.
- **Example:** 
  ```dart
  var age = 25; // Dart infers that age is of type int
  var name = "John"; // Dart infers that name is of type String
  ```

### `dynamic`:

- **Usage:** `dynamic variableName = value;`
- **Meaning:** The `dynamic` keyword allows a variable to hold values of any type. The type checking is done at runtime rather than compile-time.
- **Example:** 
  ```dart
  dynamic myVariable = 42; // myVariable can hold an int
  myVariable = "Hello"; // myVariable can now hold a String
  ```

### When to Use:

- Use `var` when you want Dart to infer the type based on the assigned value, and you still want type safety.
- Use `dynamic` when you need a variable that can hold values of any type, but be cautious as it sacrifices some of Dart's static type checking.
