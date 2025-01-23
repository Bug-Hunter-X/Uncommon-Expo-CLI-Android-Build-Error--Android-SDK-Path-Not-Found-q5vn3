# Uncommon Expo CLI Android Build Error: Android SDK Path Not Found

This repository demonstrates an uncommon error encountered when building an Android app using the Expo CLI.  Even with a correctly installed and configured Android SDK, the build process fails due to Expo's inability to locate the SDK.  This issue is not frequently reported and likely stems from subtle misconfigurations within the Expo environment or system-level path variables.

The `bug.js` file contains a simple Expo app setup to reproduce the problem. `bugSolution.js` shows steps to solve the issue.

## Reproducing the Bug

1. Clone this repository.
2. Run `npm install`.
3. Attempt to build the Android app using `expo build:android`.  The build should fail with an error message about an incorrect SDK path.

## Solution

The solution involves verifying and correcting the Android SDK path within your system environment and Expo configuration.

Refer to `bugSolution.js` for a detailed explanation of potential fixes.