# Ashraful AI Autopilot

An Android application foundation for AI-assisted video creation, social account management, content scheduling, and publishing workflows.

## Phase 1 status

This phase contains the initial Android app structure and user interface:

- Dashboard screen
- Accounts screen
- Scheduler screen
- Settings screen
- Bottom navigation
- Jetpack Compose theme
- GitHub Actions workflow for building a debug APK

**Important:** AI video generation, social account authorization, automatic scheduling, and publishing are not implemented in Phase 1. They require later development, secure backend services, and the relevant platform APIs and permissions.

## Build

The GitHub Actions workflow builds the debug APK when code is pushed to the `main` or `master` branch. It can also be started manually from the Actions tab using **Run workflow**.

The generated APK is available in the workflow run's Artifacts section.

## Requirements

- JDK 17
- Gradle 8.10.2
- Android SDK Platform 35

## Package

`com.ashraful.autopilot`
