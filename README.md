# Flutter-Sencha WebView Bridge

A hybrid application that enables seamless communication between Flutter native features and Sencha web framework through WebView integration.

## Features

- Two-way communication between Flutter and Sencha framework
- Native geolocation integration
- Secure credential storage
- Custom message handling
- URL scheme handling (tel:, https:, etc.)
- Google Maps integration
- File download support
- Cache management
- State persistence

## Architecture

This application implements a multi-layer communication system:
1. Flutter Native Layer - Handles device-specific features
2. WebView Bridge - Manages communication between native and web
3. Sencha Web Layer - Handles business logic and UI

## Setup

### Prerequisites
- Flutter SDK
- Dart SDK
- Sencha Framework
- Required Flutter packages (see pubspec.yaml)

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/flutter-sencha-webview-bridge.git
```

2. Install dependencies
```bash
flutter pub get
```

3. Configure your base URL in the application

## Usage

### Message Handling
The application supports various message types between Flutter and Sencha:
- Location requests
- Credential management
- URL handling
- Navigation controls

### Security
- Implements secure storage for credentials
- Handles permissions appropriately
- Manages WebView security settings

## Contributing
Contributions are welcome! Please read our contributing guidelines and submit pull requests to our GitHub repository.
