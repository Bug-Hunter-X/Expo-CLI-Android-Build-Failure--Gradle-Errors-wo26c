# Expo CLI Android Build Failure: Gradle Errors

This repository demonstrates a common error encountered when building Android apps using the Expo CLI. The error is characterized by failures during the Gradle build process, often due to missing or misconfigured Android SDK components, improperly set environment variables, or conflicting dependencies.

## Problem

The Expo CLI's `eas build --platform android` (or similar commands) fails with Gradle error messages.  These messages can vary but generally point to problems within the Android build system.  Common causes include:

* **Missing or Incorrect Android SDK Components:** Necessary Android build tools or APIs might be absent.
* **Environment Variable Issues:**  Environment variables like `ANDROID_HOME` might be incorrectly configured or not set.
* **Dependency Conflicts:** Conflicting dependencies in the project's `build.gradle` files can cause build failures.
* **Network Connectivity:** Issues with internet access during dependency downloads can interrupt the build.

## Solution

The provided solution demonstrates how to resolve this issue by verifying the Android SDK setup, checking environment variables, resolving dependency conflicts and ensuring network connectivity.

The solution includes steps for checking the correct installation of the Android SDK build-tools, ensuring that the `ANDROID_HOME` environment variable is set correctly, resolving any dependency conflicts in `build.gradle` files, and verifying network connectivity during the build process.   It also suggests checking the project's `gradle.properties` file for potential issues.
