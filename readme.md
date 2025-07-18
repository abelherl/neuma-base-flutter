# 🌬️ Neuma Base Flutter

### 💡 What is Neuma?
Derived from the Greek word "pneuma" meaning breath or spirit, this base is designed to bring life into your Flutter projects without getting in your way 🤩

**Neuma Base Flutter** is a lightweight, scalable Flutter project starter with a feature-first architecture, Domain-Driven Design (DDD)-inspired folder structure — designed for rapid prototyping and real-world app development. Ideal as a scalable base template for production-ready projects or experiments.

### 🧱 Project Structure

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
├── features/         # Modular feature-first structure
│   ├── home/
│   │   ├── domain/       # Entities, usecases, abstract repos
│   │   ├── presentation/ # UI widgets, screens
│   │   └── state/        # State management (e.g. cubits/providers)
│   └── profile/          # (Placeholder for other features)
│
├── routing/          # App routing setup
│   └── my_routing.dart
│
├── shared/           # Shared UI & logic across features
│   ├── dialogs/
│   ├── extensions/
│   └── widgets/
│
├── tests/        # Testing files and mocks
│
├── main.dart         # Entry point
```

### 🚀 Getting Started

1. Clone the repo
```bash
git clone https://github.com/your-username/neuma-base-flutter.git
cd neuma-base-flutter
```

2. Install packages
```bash
flutter pub get
```

3. Run the app
```bash
flutter run
```

### 🛠️ Future Plan
✅ Clean folder separation with feature-first approach
🔜 Integrate mason template for CLI bootstrapping
🔜 Multiple base templates (e.g. Bloc, Provider, Riverpod, Getx)
🔜 Optional pre-setup CLI toolchain

### 📄 License
MIT License. Use freely and contribute!