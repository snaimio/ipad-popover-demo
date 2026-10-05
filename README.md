<div align="center">

# 📱 iPadPopoverDemo
### iPadOS Adaptive Multi-Column Navigation & Popover Settings Architecture

[![iPadOS](https://img.shields.io/badge/iPadOS-17.0%2B-000000?style=for-the-badge&logo=apple&logoColor=white)](https://developer.apple.com/ipados/)
[![Swift](https://img.shields.io/badge/Swift-5.9%2B-F05138?style=for-the-badge&logo=swift&logoColor=white)](https://swift.org/)
[![SwiftUI](https://img.shields.io/badge/UI-Adaptive%20SplitView-0071E3?style=for-the-badge)](https://developer.apple.com/xcode/swiftui/)
[![License](https://img.shields.io/badge/License-MIT-CEFF00?style=for-the-badge&logoColor=black)](LICENSE)

<br/>

**A native iPadOS application demonstrating adaptive NavigationSplitView layouts, modal popover configurations, and centralized state store management.**

</div>

<br/>

---

## 📌 Technical Overview
**iPadPopoverDemo** is designed specifically to leverage the larger form factor of iPadOS. It implements multi-column split navigation (`RootView.swift` / `DetailView.swift`) and contextual popover presentation with persistent settings state.

### 💼 Technical Highlights
- **NavigationSplitView Architecture**: Multi-pane navigation supporting sidebar, content, and detail columns.
- **Contextual Popover Modals**: Interactive `.popover` presentations for in-place settings adjustments (`SettingsPopoverView.swift`).
- **Observable Store Pattern**: Centralized `SettingsStore.swift` managing global app preferences.

---

## 🚀 Setup & Run
1. Clone the repository:
   ```bash
   git clone https://github.com/snaimio/ipadPopoverDemo2026.git
   cd ipadPopoverDemo2026
   open ipadPopoverDemo2026.xcodeproj
   ```
2. Run on iPad Simulator in Xcode (`⌘ + R`).

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author
**Sheikh Naim**  
*Mobile & Full-Stack Web Developer*  
- **LinkedIn**: [linkedin.com/in/snaimio](https://www.linkedin.com/in/snaimio)  
- **GitHub**: [@snaimio](https://github.com/snaimio)  
- **Portfolio**: [snaimio.github.io](https://snaimio.github.io)
