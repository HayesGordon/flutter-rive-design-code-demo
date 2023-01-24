# Optimised Animation's for Aashu-Dubey Demo App
The original code can be found [here](https://github.com/Aashu-Dubey/flutter-samples).

This fork adds some performance improvements to the animations to better showcase what Flutter can do.
The optimisations are:
- Using `AnimatedBuilder` instead of calling `setState` on each animation tick. This avoid unnecessary rebuilds and can allow for caching of child widgets
- Introduce some [RepaintBoundary's](https://www.youtube.com/watch?v=Nuni5VQXARo)

# Animated App with Rive and Flutter

An application with interactive UI and animations, with custom UI components like Bottom TabBar and SideBar, and using animated assets from [Rive](https://rive.app).

<p align="center">
  <img alt="Flutter + Rive UI Preview" src="https://user-images.githubusercontent.com/46301285/212767021-ce434bc0-d6f8-41c1-a17a-360ea225009b.png" height="250px">
</p>

---

## 👀 This is how it looks

https://user-images.githubusercontent.com/46301285/213805689-d5c8eb3f-12d0-42ef-bdae-4bd857113579.mp4

## 📦 Packages used

1. [rive](https://pub.dev/packages/rive): To render and control the [Rive assets](../../assets/rive_app/rive).

## 🌻 Motivation

This app is a full Flutter replication of [this SwiftUI course](https://designcode.io/swiftui-rive-animated-app) by [@MengTo](https://twitter.com/MengTo).

## 🔗 Links

- [SwiftUI + Rive](https://designcode.io/swiftui-rive-animated-app): Original course in SwiftUI.
- [Ionic Rive](https://github.com/Aashu-Dubey/Ionic-UI-Templates/tree/main/ionic_ui_templates/src/app/templates/course-rive): Ionic + Angular version for the same.
- [Twitter Post](https://twitter.com/aashudubey_ad/status/1616536431010406400)
