# WebRTC-iOS-Binary

Precompiled **Google WebRTC XCFramework for iOS** distributed via GitHub Releases for use with **Swift Package Manager (SPM)**.

This repository provides a binary distribution of WebRTC to avoid building from source and to enable easy integration into iOS applications and SDKs.

---

## 📦 Overview

This package provides:

- Precompiled `WebRTC.xcframework`
- iOS device + simulator support
- Swift Package Manager compatible binary distribution
- Faster integration without manual WebRTC builds

---

## 🚀 Installation (Swift Package Manager)

### Add Package Dependency

In your `Package.swift`:

```swift
.binaryTarget(
    name: "WebRTC",
    url: "https://github.com/imentiv/WebRTC-iOS-Binary/releases/download/v1.0.0/WebRTC.xcframework.zip",
    checksum: "REPLACE_WITH_CHECKSUM"
)
```

---

## 📱 Requirements

- iOS 13+
- Xcode 15+
- Swift Package Manager

---

## 📂 Included Platforms

- iOS (Device)
- iOS Simulator

---

## 🎯 Purpose

This repository exists to:

- Provide a ready-to-use WebRTC binary
- Reduce build time and complexity
- Enable easy SDK integration
- Avoid maintaining custom WebRTC builds

---

## 📌 Versioning

This project follows semantic versioning:

vMAJOR.MINOR.PATCH

Example:
- v1.0.0 — Initial release

---

## 📄 License

This distribution contains Google's WebRTC framework.  
Refer to the official WebRTC project for licensing details:

https://webrtc.org

---

## 👨‍💻 Maintained By

Imentiv
