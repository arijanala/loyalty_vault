# Loyalty Vault

Loyalty Vault is a cross‑platform Flutter application for managing loyalty cards and rewards in one place.  
The project currently uses the standard Flutter project layout and is ready to be extended into a production‑ready app.

---

### Features (planned / suggested)

- Store and manage multiple loyalty cards in one app
- Quick access to barcodes / QR codes at checkout
- Organize cards by merchant or category
- Cloud backup & sync across devices (future)
- Dark mode and responsive layout for mobile and desktop (future)

Update this list to reflect what you’ve actually implemented so far.

---

### Tech Stack

- **Framework**: Flutter
- **Languages**: Dart (UI & logic), plus platform‑specific code for:
  - Android
  - iOS
  - Web
  - Windows
  - macOS
  - Linux
- **Build / tooling**:
  - `pubspec.yaml` for dependencies and configuration
  - `analysis_options.yaml` for Dart analysis rules

---

### Getting Started

#### Prerequisites

- Flutter SDK installed  
  See the official docs: https://docs.flutter.dev/get-started/install
- A recent version of:
  - Android Studio, VS Code, or your preferred IDE
  - Xcode (for iOS / macOS builds)
  - Required platform SDKs / toolchains (Android, Windows, Linux, etc.)

Verify Flutter is installed correctly:

```bash
flutter doctor
```

#### Clone the repository

```bash
git clone https://github.com/arijanala/loyalty_vault.git
cd loyalty_vault
```

#### Install dependencies

```bash
flutter pub get
```

#### Run the app

Mobile or desktop (depending on your configured devices):

```bash
flutter run
```

Web:

```bash
flutter run -d chrome
```

---

### Project Structure

Key folders:

- `lib/` – Dart source code for the Flutter app (UI, state management, business logic)
- `android/`, `ios/`, `macos/`, `linux/`, `windows/`, `web/` – Platform‑specific runners and configuration
- `test/` – Unit and widget tests
- `pubspec.yaml` – App metadata, dependencies, and assets

---

### Development

- **Code style**: Follows Flutter / Dart best practices (`dart format`, `flutter analyze`)
- **Testing**:

```bash
flutter test
```

Consider adding:

- State management (e.g. Provider, Riverpod, Bloc)
- CI (GitHub Actions) to run tests and analysis on each push

---

### Roadmap (example)

- [ ] Define core data model for loyalty cards
- [ ] Implement card list and details screens
- [ ] Add barcode / QR code display
- [ ] Add persistent storage
- [ ] Implement syncing / backup

---

### Contributing

This is currently a personal learning / portfolio project.  
If you’d like to suggest changes or improvements, feel free to open an issue or a pull request.

---

### License

Add your preferred license here (for example, MIT, Apache 2.0, or keep it proprietary).
