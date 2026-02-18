# Birdle

A Flutter mobile game implementation of Wordle. Guess the 5-letter word in limited attempts with color-coded feedback.

## Features

- **Wordle Gameplay**: Guess a randomly selected 5-letter word with up to 5 attempts
- **Color-Coded Feedback**: 
  - 🟩 Green: Correct letter in the correct position
  - 🟨 Yellow: Correct letter in the wrong position
  - ⬜ Gray: Letter not in the word
- **Input Validation**: Only accepts valid English words from the Wordle dictionary
- **Cross-Platform**: Runs on iOS, Android, Web, macOS, Windows, and Linux
- **Animated UI**: Smooth animations for an engaging user experience

## How to Play

1. Launch the app and you'll see an empty 5x5 grid
2. Type your first guess (5 letters)
3. Submit your guess and receive color feedback
4. Use the feedback to refine your next guess
5. Win by guessing the word in 5 or fewer attempts!

## Requirements

- Flutter SDK 3.10.0 or higher
- Dart SDK 3.10.0 or higher

## Getting Started

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd birdle

# Install dependencies
flutter pub get
```

### Run

```bash
# Run on connected device or emulator
flutter run

# Run on specific platform
flutter run -d chrome        # Web
flutter run -d macos         # macOS
flutter run -d windows       # Windows
flutter run -d linux         # Linux
```

### Build

```bash
# Build APK (Android)
flutter build apk

# Build iOS
flutter build ios

# Build Web
flutter build web
```

## Project Structure

```
lib/
├── main.dart      # App entry point and UI components
├── game.dart      # Game logic and state management
pubspec.yaml       # Project configuration and dependencies
```

## Dependencies

- **flutter**: Flutter SDK
- **legal_wordle_words**: Valid Wordle word lists

## License

This project is open source.
