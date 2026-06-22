# Crafty Bay E-Commerce App

Crafty Bay is a modern, feature-rich e-commerce application built with Flutter. It follows a clean architecture with a strict Separation of Concerns (SoC) to ensure scalability, maintainability, and testability.

## 🚀 Status: In Progress
This project is currently under active development.

## 📸 Screenshots
<p align="center">
  <!-- Add your screenshots here -->
  <img width="420" height="235" alt="pr4" src="https://github.com/user-attachments/assets/e786f09b-d50c-4417-9ccf-4812cee67454" />
</p>

## ✨ Key Features
- **🌍 Localization**: Multi-language support using `flutter_localizations` and `intl`.
- **🌗 Theme Changing**: Dynamic light and dark mode switching, persisted using `shared_preferences`.
- **🔐 Secure Authentication**: User login and authentication powered by JWT (JSON Web Tokens).
- **🏗️ Strict SoC Architecture**: Clean separation of layers (Data, Domain, Presentation) for better modularity.
- **🛠️ State Management**: Efficient state handling across the app using the **Provider** package.
- **📦 API Pagination**: Optimized data loading for product lists and categories.
- **🛒 Cart Management**:
  - Add/Remove items from the cart.
  - Real-time cart state updates.
  - Cart total price summary calculation.
- **🎨 Modern UI/UX**:
  - Interactive **Carousel Sliders** for promotions and products.
  - SVG icon support for crisp visuals.
  - Optimized image loading with **Cached Network Image**.
- **📌 Version Control**: Managed with **FVM** (Flutter Version Manager) for consistent development environments.

## 🛠️ Tech Stack & Libraries
- **Language**: [Dart](https://dart.dev/)
- **Framework**: [Flutter](https://flutter.dev/)
- **State Management**: [Provider](https://pub.dev/packages/provider)
- **Local Storage**: [Shared Preferences](https://pub.dev/packages/shared_preferences)
- **Network**: [HTTP](https://pub.dev/packages/http)
- **UI Components**:
  - `carousel_slider`
  - `flutter_svg`
  - `pin_code_fields`
  - `cached_network_image`
- **Backend Services**: Firebase Core, Analytics, and Crashlytics.

## 🏗️ Architecture
The project follows a **Feature-First** structure with strict **Separation of Concerns**:
```text
lib/
├── app/          # App-wide configurations (theme, routes)
├── core/         # Common utilities, constants, and network helpers
├── features/     # Feature-specific modules (auth, cart, home, etc.)
│   ├── data/     # Models and Repositories
│   └── presentation/ # UI Screens and Providers
└── l10n/         # Localization files
```

## ⚙️ Getting Started

### Prerequisites
- [FVM](https://fvm.app/) installed on your machine.
- Flutter SDK (version specified in `.fvmrc` or `pubspec.yaml`).

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/of18_e_commerce_project_1.git
   ```
2. Navigate to the project directory:
   ```bash
   cd of18_e_commerce_project_1
   ```
3. Install dependencies using FVM:
   ```bash
   fvm flutter pub get
   ```
4. Run the app:
   ```bash
   fvm flutter run
   ```

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
