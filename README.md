# SmartSpectra SDK for iOS

SmartSpectra measures vital signs — heart rate, breathing rate, HRV, and more — from camera video or frames supplied by your app.

## Installation

Add the package via Swift Package Manager:

```text
https://github.com/Presage-Security/SmartSpectra-Swift
```

In Xcode: **File** → **Add Package Dependencies...** → enter the URL above.

For repeatable production builds, select a stable version such as `3.0.0`.
Use the `main` branch only when testing the latest final public release before pinning a version.

For release candidates and other prereleases, select the `rc` branch. The `rc` branch tracks the
latest prerelease package manifest, for example `3.0.0-rc.14`. For reproducible prerelease builds,
pin the exact prerelease version when your package manager supports it.

## Documentation

Full integration guide, API reference, and examples:

[Swift quickstart](https://github.com/Presage-Security/SmartSpectra/blob/main/swift/README.md)

[Swift API reference](https://github.com/Presage-Security/SmartSpectra/blob/main/swift/docs/api-reference.md)

[Custom camera and video input](https://github.com/Presage-Security/SmartSpectra/blob/main/swift/docs/headless-mode.md#use-your-own-camera-or-video-source)
shows how to use `useCustomInput()` with `CVPixelBuffer` and `CMSampleBuffer`,
including ownership, timestamps, and switching back to SDK camera capture.

Sample apps and broader SDK examples live in the main SmartSpectra repository:

[github.com/Presage-Security/SmartSpectra](https://github.com/Presage-Security/SmartSpectra)

## Support

[support@presagetech.com](mailto:support@presagetech.com) | [GitHub Issues](https://github.com/Presage-Security/SmartSpectra-Swift/issues)
