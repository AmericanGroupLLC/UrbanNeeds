# UrbanNeeds

> App that finds a service to your needs — a React Native consumer app for discovering local services on Android & iOS.

[![CI](https://github.com/AmericanGroupLLC/UrbanNeeds/actions/workflows/ci.yml/badge.svg)](https://github.com/AmericanGroupLLC/UrbanNeeds/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Android%20%7C%20iOS-blue.svg)]()

## Product

UrbanNeeds is a consumer mobile application that helps users discover and connect with services tailored to their everyday urban needs. Built with React Native, it ships natively to both Android and iOS from a single JavaScript codebase.

## Features

- 🔎 **Service discovery** — find services that match your needs
- 📱 **Cross-platform** — single codebase for Android & iOS
- ⚡ **React Native** — native performance with rapid iteration
- 🎨 **Consumer-grade UX** — designed for everyday use
- 🧪 **Jest unit tests** — built-in testing infrastructure

## Quickstart

```bash
# Install dependencies
yarn install

# Run on Android (emulator or connected device must be available)
yarn react-native run-android

# Run on iOS (macOS only; requires Xcode)
yarn react-native run-ios

# Start the Metro bundler manually
yarn start

# Run tests
yarn test
```

> **Note:** The `package.json` does not currently define `yarn android` / `yarn ios` shortcuts. Use the `react-native run-*` commands above, or add the shortcut scripts as needed.

### Prerequisites

- **Node.js** (LTS recommended)
- **Yarn** (classic)
- **Android Studio** + Android SDK + an emulator/device for Android builds
- **Xcode** (macOS) for iOS builds
- **JDK 8+** for Android Gradle builds

## Repo Layout

```
UrbanNeeds/
├── App.js                  # Root React Native component
├── index.js                # App entry point
├── app.json                # App display name & metadata
├── package.json            # JS dependencies & scripts
├── __tests__/              # Jest unit tests
├── android/                # Native Android project (Gradle)
│   ├── app/
│   ├── build.gradle
│   └── settings.gradle
├── ios/                    # Native iOS project (Xcode)
│   ├── urbanapp/
│   ├── urbanapp-tvOS/
│   └── urbanapp.xcodeproj/
├── .github/
│   ├── CODEOWNERS
│   ├── ISSUE_TEMPLATE/
│   └── workflows/ci.yml    # Lint + typecheck + Android build
├── CHANGELOG.md
├── LICENSE
└── README.md
```

## Umbrella

This repo is part of the AmericanGroupLLC product portfolio. See the umbrella org page for related projects: <https://github.com/AmericanGroupLLC>.

## Contributing

- File issues using the templates in [`.github/ISSUE_TEMPLATE`](.github/ISSUE_TEMPLATE).
- Code owners are defined in [`.github/CODEOWNERS`](.github/CODEOWNERS).
- Notable changes are tracked in [`CHANGELOG.md`](CHANGELOG.md).

## License

Released under the [MIT License](LICENSE). © 2026 AmericanGroupLLC.
