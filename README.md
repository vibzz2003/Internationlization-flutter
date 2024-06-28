# Flutter Internationalization Demo

This project demonstrates how to implement internationalization (i18n) in a Flutter application. It supports multiple languages including English, Hindi, Arabic, French, and Portuguese.

## Features

- Supports 5 languages: English, Hindi, Arabic, French, and Portuguese
- Uses Flutter's built-in localization system
- Demonstrates animated text in different languages
- Provides instructions for changing languages

## Screenshots

Here are screenshots of the application running in different languages:

### English
![English Version](https://github.com/vibzz2003/Internationlization-flutter/blob/main/static/Screenshot%20(384).png)

### Hindi
![Hindi Version](https://github.com/vibzz2003/Internationlization-flutter/blob/main/static/Screenshot%20(385).png)

### Arabic
![Arabic Version](https://github.com/vibzz2003/Internationlization-flutter/blob/main/static/Screenshot%20(386).png)

### French
![French Version](https://github.com/vibzz2003/Internationlization-flutter/blob/main/static/Screenshot%20(387).png)

### Portuguese
![Portuguese Version](https://github.com/vibzz2003/Internationlization-flutter/blob/main/static/Screenshot%20(388).png)

## Getting Started

To run this project:

1. Ensure you have Flutter installed on your machine.
2. Clone this repository.
3. Run `flutter pub get` to install dependencies.
4. Run `flutter gen-l10n` to generate localization files.
5. Use `flutter run` to start the application.

## Project Structure

- `lib/main.dart`: The main application file.
- `lib/l10n/`: Contains ARB files for each supported language.
- `l10n.yaml`: Configuration file for Flutter's localization system.

## Changing Languages

The app will automatically use the device's language settings. To test different languages, you can modify the `locale` property in the `MaterialApp` widget in `main.dart`:

```dart
return MaterialApp(
  // ...
  locale: const Locale('hi', ''), // Force Hindi, change as needed
  // ...
);
