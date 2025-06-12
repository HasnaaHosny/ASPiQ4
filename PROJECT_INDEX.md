# ASPiQ3 Project Index

## Project Overview
This is a Flutter project that appears to be an application with authentication, testing, and reporting features.

## Directory Structure

### Root Directory
- `lib/` - Main source code directory
- `assets/` - Static assets (images, fonts, etc.)
- `test/` - Test files
- `android/`, `ios/`, `web/`, `linux/`, `macos/`, `windows/` - Platform-specific code
- `pubspec.yaml` - Project dependencies and configuration
- `analysis_options.yaml` - Dart/Flutter analysis configuration

### Source Code Structure (`lib/`)

#### Core Components
- `main.dart` - Application entry point
- `enums.dart` - Enumeration definitions
- `injection_container.dart` - Dependency injection setup

#### Feature Modules
- `auth_services.dart` - Authentication services
- `applicition_theme/` - Application theming
- `core/` - Core functionality
- `emotion/` - Emotion-related features
- `features/` - Main feature modules
- `login/` - Login functionality
- `registration/` - User registration
- `Report/` - Reporting features
- `screens/` - Application screens
- `session/` - Session management
- `test/` - Test-related features
- `test3months/` - Three-month test functionality
- `monthly_test/` - Monthly testing features

#### Supporting Directories
- `models/` - Data models
- `services/` - Service layer
- `widget/` and `widgets/` - Reusable UI components

## Key Files
1. `main.dart` - Application entry point
2. `auth_services.dart` - Authentication implementation
3. `enums.dart` - Enumeration definitions
4. `injection_container.dart` - Dependency injection setup

## Development Guidelines
1. Follow the existing directory structure for new features
2. Place new widgets in the `widgets/` directory
3. Add new services in the `services/` directory
4. Create new models in the `models/` directory
5. Follow Flutter best practices for code organization

## Testing
- Unit tests are located in the `test/` directory
- Platform-specific tests are in their respective platform directories

## Dependencies
See `pubspec.yaml` for the complete list of project dependencies.

## Getting Started
1. Ensure Flutter is installed
2. Run `flutter pub get` to install dependencies
3. Use `flutter run` to start the application

## Notes
- The project uses dependency injection for better code organization
- Authentication is handled through dedicated services
- The application supports multiple platforms (Android, iOS, Web, Desktop) 