# flutter_vsac_example

 - Android Build 
[![Build status](https://build.appcenter.ms/v0.1/apps/0fe58890-14f3-4fe8-9212-cf65fb5e8d70/branches/master/badge)](https://appcenter.ms)

A new Flutter project using VSAC build feature.

## Android Setup

- Create (or copy) the gradle files (gradlew, gradlew.bat and gradle directory) to your project root.
- Add a settings.gradle file in the root of the project like the one on this repository.
- add a appcenter-post-close.sh script in the root of the project (project/app/).

> if there is an error like  
> ##[error]Error: spawn EACCES
> be sure to modify the permissions of the gradlew directory and the android
> or do this on the build script


## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
