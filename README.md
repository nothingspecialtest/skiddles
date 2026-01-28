# skiddles

A collection of development tools and features for Ubuntu development environments.

## Features

### Android SDK
Install and configure the Android SDK for Android development.

**Installation:**
```bash
bash android-sdk-install
```

This script will:
- Install Java Development Kit (JDK)
- Install Android SDK dependencies
- Download and extract Android SDK Command Line Tools
- Set up environment variables (ANDROID_HOME, PATH)
- Install common Android SDK components (platform-tools, platforms, build-tools)
- Accept Android SDK licenses

After installation, reload your shell environment:
```bash
source ~/.bashrc
```

To verify the Android SDK is properly installed:
```bash
sdkmanager --list
```