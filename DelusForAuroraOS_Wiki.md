
# DelusForAuroraOS Wiki

Welcome to the **DelusForAuroraOS** Wiki — your comprehensive guide to building and running the Delus client on **Aurora OS**, an independent Russian mobile OS. This repository is part of the broader REChain Network and Katya® initiatives to create decentralized, privacy-centric, and censorship-resistant systems.

---

## 📦 Overview

**DelusForAuroraOS** provides a customized version of the Delus PWA engine optimized for compatibility with **Aurora OS**, enabling full support for:
- Privacy-first social networking
- Offline-ready and edge-compatible applications
- Secure messaging and distributed file sharing
- Integration with REChain decentralized identity (DID)

---

## 📁 Repository Structure

```
DelusForAuroraOS/
├── aurora-adapter/         # Core logic and adaptation layer for Aurora OS
├── assets/                 # Static assets and media
├── lib/                    # Flutter application source code
├── platform/aurora/        # Platform-specific services, permissions, and APIs
├── test/                   # Test cases
└── README.md               # Quick start and setup guide
```

---

## 🚀 Getting Started

### Prerequisites
- Aurora OS SDK and device/emulator
- Flutter SDK (3.13 or higher)
- Dart SDK (3.1+)
- REChain CLI (optional but recommended)

### Installation
```bash
git clone https://github.com/sorydima/DelusForAuroraOS.git
cd DelusForAuroraOS
flutter pub get
flutter run -d aurora
```

### Build for Aurora
```bash
flutter build apk --target-platform=android-arm64 --release
```
> *Aurora OS is compatible with Android Runtime environments; ensure native dependencies are ported properly.*

---

## 🔐 Security & Privacy
- Uses end-to-end encryption for messaging
- Local-first storage with REChain IPFS-layer integration
- DID support (Decentralized Identifiers)

---

## 🤝 Related Projects
- [Katya ® 👽 OS](https://github.com/sorydima/Katya-.git)
- [Delus-PWA-Engine](https://github.com/REChain-Network-Solutions/Delus-PWA-Engine.git)
- [REChain Network Solutions](https://github.com/REChain-Network-Solutions)

---

## 🧩 Modules & Features
- Modular chat engine (XMPP + custom protocol)
- Decentralized news feed
- Secure marketplace integration
- QR code-based login and DID authentication

---

## 📅 Roadmap
- [x] Initial Aurora adaptation
- [x] Support for DID
- [ ] Voice & video call integration
- [ ] Local mesh support via Bluetooth/Wi-Fi
- [ ] Full offline-first deployment via REChain edge nodes

---

## 🛠️ Contribution Guide
We welcome contributions via PRs or issues. Please refer to the `CONTRIBUTING.md` once available, or contact @sorydima.
