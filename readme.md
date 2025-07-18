![neuma header](https://res.cloudinary.com/dp3fqnmmg/image/upload/v1752827195/GitHub_-_Neuma_Base_Flutter_1_fpg9be.png)

## 💡 What is Neuma?
Derived from the Greek word "pneuma" meaning breath or spirit, Neuma Base Flutter is designed to bring life into your Flutter projects without getting in your way 🤩

It’s a lightweight yet scalable Flutter starter with a feature-first architecture and a DDD-inspired folder structure — perfect for rapid prototyping, real-world app development, and clean production-ready codebases.

## 🧱 Project Structure

```bash
lib/
├── core/             # App-wide configurations and helpers
│   ├── constants/    # App constants (colors, strings, keys)
│   ├── services/     # Core service implementations (e.g., navigation, logging)
│   ├── theme/        # Centralized theming
│   └── utils/        # Utility functions
│
├── data/             # Low-level data layer (network, DB, etc.)
│   ├── api/          # API clients and endpoints
│   ├── database/     # Local DB interfaces
│   ├── models/       # DTOs and data representations
│   └── repositories/ # Data sources implementation
│
├── features/             # Modular feature-first structure
│   ├── home/
│   │   ├── domain/       # Entities, usecases, abstract repos
│   │   ├── presentation/ # UI widgets, screens
│   │   └── state/        # State management (e.g. cubits/providers)
│   └── profile/          # (Placeholder for other features)
│
├── routing/          # App routing setup
│
├── shared/           # Shared UI & logic across features
│   ├── dialogs/
│   ├── extensions/
│   └── widgets/
│
├── tests/            # Testing files and mocks
│
├── main.dart         # Entry point
```

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/abelherl/neuma-base-flutter.git
cd neuma-base-flutter
```

### 2. Install packages
```bash
flutter pub get
```

### 3. Run the app
```bash
flutter run
```

### 4. *(Optional)* Update ```readme.md``` file
You can alter this readme file for your project if needed.

## 🛠️ Future Plan
* ✅ Clean folder separation with feature-first approach
* 🔜 Integrate mason template for CLI bootstrapping
* 🔜 Multiple base templates (e.g. Bloc, Provider, Riverpod, Getx)
* 🔜 Optional pre-setup CLI toolchain

## 📄 License
[MIT](./LICENSE)
