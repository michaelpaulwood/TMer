# TMer - Apple Watch Meditation Timer

A minimalist meditation timer app designed specifically for Apple Watch, featuring customizable durations, rest periods, and haptic feedback patterns.

## Features

### Core Functionality
- **Meditation Timer**: Guided meditation sessions with visual circular progress indicator
- **Rest Periods**: Configurable rest time between meditation sessions
- **Haptic Feedback**: Three intensity levels (gentle, standard, strong) for session transitions
- **Water Lock Integration**: Automatically activates during meditation to prevent accidental touches

### Customization Options
- **Timer Durations**: Choose from preset options (10min, 20min) or set custom durations
- **Rest Period Settings**: Configurable rest time between sessions
- **Haptic Patterns**: Personalize feedback intensity for your preference

### User Interface
- **Clean Design**: Minimal, distraction-free interface optimized for Apple Watch
- **Card-Based Navigation**: Intuitive selection of timer options
- **Progress Visualization**: Animated circular progress indicator
- **Session States**: Clear visual feedback for meditation, rest, and completion phases

## Screenshots

*Coming soon - screenshots of the app in action*

## Installation

### Requirements
- Apple Watch (watchOS compatible)
- iPhone paired with Apple Watch
- Xcode (for development/testing)
- Apple Developer account (free for personal use, paid for App Store)

### Development Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/michaelpaulwood/TMer.git
   cd TMer
   ```

2. Open `TMer.xcodeproj` in Xcode

3. Select your Apple Watch as the target device

4. Build and run (⌘+R) to install on your watch

### Free Developer Account
With a free Apple Developer account:
- Sign in with your Apple ID in Xcode → Preferences → Accounts
- Apps expire after 7 days (requires reinstallation)
- Limited to 3 apps per device
- No App Store distribution

## Technical Details

### Architecture
- **Framework**: SwiftUI for Apple Watch
- **State Management**: ObservableObject pattern with UserDefaults persistence
- **Navigation**: NavigationStack for seamless view transitions
- **Haptics**: WatchKit haptic feedback system

### Key Components
- `ContentView.swift` - Main entry point and welcome screen
- `MainMenuView.swift` - Timer selection interface
- `TimerView.swift` - Core meditation timer with progress indicator
- `AppSettings.swift` - User preferences and persistence
- `MeditationSession.swift` - Session data models and timer states

### Features in Detail
- **Timer States**: Stopped, Meditating, Resting, Completed
- **Settings Persistence**: UserDefaults for maintaining user preferences
- **Haptic Integration**: Three-level intensity system for accessibility
- **Water Lock**: Automatic activation during active meditation sessions

## Usage

1. **Start the App**: Launch TMer on your Apple Watch
2. **Select Duration**: Choose from preset times or create custom duration
3. **Begin Session**: Tap to start your meditation
4. **Water Lock**: The watch automatically locks during sessions
5. **Follow Progress**: Watch the circular indicator fill as you meditate
6. **Rest Period**: Optional rest time between multiple sessions
7. **Completion**: Receive haptic feedback when session ends

## Contributing

This is an open-source project. Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.

### Development Guidelines
- Follow SwiftUI best practices
- Maintain accessibility features
- Test on actual Apple Watch hardware when possible
- Keep the interface minimal and distraction-free

## Future Enhancements

- [ ] Multiple meditation themes/sounds
- [ ] Session history and statistics
- [ ] Integration with Apple Health
- [ ] Custom meditation programs
- [ ] Social sharing features
- [ ] Widget support

## License

This project is open source. See LICENSE file for details.

## Author

Michael Paul Wood - [connect@michaelpaulwood.com](mailto:connect@michaelpaulwood.com)

## Support

For questions, issues, or feature requests, please open an issue on GitHub or contact the developer directly.

---

*Built with ❤️ for mindful moments on your wrist*