<div align="center">

# 📱 iPad Popover & SplitView Suite
### Native iPadOS Multi-Column Navigation & Adaptive Popover Presentation Architecture

[![iPadOS](https://img.shields.io/badge/iPadOS-17.0%2B-000000?style=for-the-badge&logo=apple&logoColor=white)](https://developer.apple.com/ipados/)
[![Swift](https://img.shields.io/badge/Swift-5.9%2B-F05138?style=for-the-badge&logo=swift&logoColor=white)](https://swift.org/)
[![SwiftUI](https://img.shields.io/badge/UI-Adaptive%20NavigationSplitView-0071E3?style=for-the-badge&logo=swift&logoColor=white)](https://developer.apple.com/xcode/swiftui/)
[![Combine](https://img.shields.io/badge/State-ObservableObject-8B5CF6?style=for-the-badge)](https://developer.apple.com/documentation/combine)
[![License](https://img.shields.io/badge/License-MIT-CEFF00?style=for-the-badge&logoColor=black)](LICENSE)

<br/>

**A native iPadOS architecture demo demonstrating multi-pane `NavigationSplitView` hierarchies, contextual modal `.popover` presentations, and reactive environment state pipelines tailored for tablet user experiences.**

<br/>

[Overview](#-technical-overview) •
[Engineering Highlights](#-engineering-highlights) •
[Setup & Run](#-setup--run) •
[License](#-license)

</div>

<br/>

---

## 📌 Technical Overview

**iPad Popover Demo** showcases adaptive design patterns specifically optimized for iPadOS widescreen form factors. It demonstrates how to structure multi-column workflows utilizing SwiftUI's `NavigationSplitView`, render contextual popovers with custom arrow anchors, and maintain synchronized state across split view hierarchies using `ObservableObject` stores.

---

## 🏛️ Engineering Highlights

- **Multi-Column `NavigationSplitView`**: Responsive sidebar, content list, and detail panes adapting between compact and regular horizontal size classes.
- **Contextual Popover Presentation**: Clean `.popover` sheet presentation for in-place configuration changes without disrupting the primary view hierarchy.
- **Observable Store Pattern**: Centralized `SettingsStore.swift` managing global application preferences and themes via `@Published` and `@EnvironmentObject`.
- **Adaptive Layout Ergonomics**: Optimized touch targets, hover effects, and split-screen multitasking support (Slide Over & Split View).

---

## 🚀 Setup & Run

### Prerequisites
- **Xcode 15.0+**
- **iPadOS 17.0+** Simulator or Physical iPad Device

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/snaimio/ipad-popover-demo.git
   cd ipad-popover-demo
   ```

2. **Open in Xcode:**
   ```bash
   open ipadPopoverDemo2026.xcodeproj
   ```

3. **Run Application:**
   - Select an iPad Simulator (e.g. *iPad Pro 11-inch (M4)* or *iPad Air*).
   - Press **⌘ + R** to build and launch.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
