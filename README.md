# AndroidNative Plugin Fork

## Overview

This is my attempt to keep this plugin running even though official support has ended. Any changes made on this fork are not part of the official plugin at all.  The goal is to keep it functional for users who still rely on it.

## Engine Compatibility

| Engine Version | Status | Notes |
|---------------|--------|-------|
| 5.5.4         | ✅ Yes | Confirmed working |
| 5.6.1         | 🟠 Compiles | Not yet tested |
| 5.7 Preview 1 | ❓ Unknown | Not yet tested |

## Requirements

- Project must be a **C++ project** (Blueprint-only projects are not supported)
- Development environment for Android builds

## Documentation

**Official Documentation**: [https://docs.georgy.dev/android-native/overview](https://docs.georgy.dev/android-native/overview)

*Note: This documentation is for the original plugin. Some information may not apply to this community fork.*

## Getting Started



### Installation

1. Navigate to your project's `Plugins` folder
2. Clone this repository:
   ```
   git clone https://github.com/Nocxr/AndroidNative.git
   ```
3. Right-click your `.uproject` file and select "Generate Visual Studio project files"
5. Navigate to `Plugins/AndroidNative/Source/AndroidNative/Private/Java/` and add your `.java` files

### Basic Usage

**TODO:**
- [ ] Show no arg call
- [ ] Show arg call  
- [ ] Show Java to C++ callback
- [ ] Show activity usage
- [ ] Show custom arg usage

## Disclaimer

This fork is maintained on a best-effort basis. There are no guarantees of compatibility, stability, or continued maintenance. Use at your own risk.
