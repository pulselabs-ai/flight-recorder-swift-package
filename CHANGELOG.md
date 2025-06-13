# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## [1.5.1] - 2025-06-13

### Added

- Enhanced upload process
- Bug fixes & optimizations

## [1.5.0] - 2025-04-09

### Added

- New flow of using CaptureMethods with the new FlightRecorder portal

## [1.4.2] - 2025-01-29

### Added

- Bug fixes & optimizations

## [1.4.1] - 2024-11-28

### Added

- Add the new hearbeat call and minor fixes

## [1.4.0] - 2024-11-06

### Added

- Support for manual recording mode for select customers
- Crash and bug fixes

## [1.3.0] - 2024-08-01

### Added

- Custom Survey feature.
- Dynamic Styling.
- Support passing in your own Font Library.


## [1.2.2] - 2024-03-21

### Fixed

* iPad video editor issue.


## [1.2.1] - 2024-03-14

Migrated from manual installation to Swift Package Manager. If you previously installed manually:

1. Open the project within which you wish to update the SDK.
2. Right-click on the **PulseLabsFlightRecorderSDK** item in the Project Navigator and click **Delete**.
3. Click on **Move to Trash**.

Follow the setup instructions at https://pulselabs.gitbook.io/pulse-flightrecorder-docs/sdk-documentation/pulse-labs-flightrecorder-documentation/ios/install-the-sdk

### Added

* Feature to trigger a screen recording from your own code, enabling custom buttons or triggers. Learn more at https://pulselabs.gitbook.io/pulse-flightrecorder-docs/sdk-documentation/pulse-labs-flightrecorder-documentation/ios/create-custom-triggers/capture-recording
* The SDK can now be enabled or disabled by the end user by toggling the **Shake device to report feedback** option in the UI.
* The number of saved drafts can be seen in the **VIEW SAVED DRAFTS** link.

### Changed

* The screen recorder no longer relies upon Apple's ReplayKit SDK, this has allowed us to remove the permission popups, and resolve issue where jank could sometimes be seen in the videos.
