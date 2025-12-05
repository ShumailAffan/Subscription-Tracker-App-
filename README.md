# Subscription-Tracker-App-
A powerful and beautiful Flutter application designed to help you track your recurring subscriptions, analyze your spending habits, and never miss a payment again.

![App Banner](https://via.placeholder.com/1280x640.png?text=Subscription+Tracker+App)

## 🚀 Features

- **Dashboard**: View all your active subscriptions in one place with a clean, intuitive UI.
- **Analytics**: Visualize your monthly and yearly spending with interactive charts using `fl_chart`.
- **Smart Notifications**: Get reminded before your bills are due so you never pay late fees.
- **Cloud Sync**: Your data is securely synced across devices using Google Firebase.
- **Subscription Management**: Easily add, edit, and remove subscriptions with custom billing cycles.
- **Customization**:
  - **Dark/Light Mode**: Seamless theme switching.
  - **Currency Support**: Choose your preferred currency for accurate tracking.
- **Secure Authentication**: Robust login and sign-up system powered by Firebase Auth.

## 🛠️ Tech Stack

- **Framework**: [Flutter](https://flutter.dev/)
- **Language**: [Dart](https://dart.dev/)
- **State Management**: [Flutter Bloc](https://pub.dev/packages/flutter_bloc)
- **Backend**: [Firebase](https://firebase.google.com/) (Auth, Firestore, Storage)
- **Local Storage**: Shared Preferences
- **Charts**: [FL Chart](https://pub.dev/packages/fl_chart)
- **Notifications**: [Flutter Local Notifications](https://pub.dev/packages/flutter_local_notifications)

## 📸 Screenshots

| Home Screen | Analytics | Add Subscription |
|:---:|:---:|:---:|
| ![Home](https://via.placeholder.com/300x600.png?text=Home+Screen) | ![Analytics](https://via.placeholder.com/300x600.png?text=Analytics) | ![Add](https://via.placeholder.com/300x600.png?text=Add+Screen) |

## 🏁 Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- [Dart SDK](https://dart.dev/get-dart)
- A Firebase project configured for this app.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/subscription-tracker-app.git
   cd subscription-tracker-app
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Firebase Setup**
   - Create a project on [Firebase Console](https://console.firebase.google.com/).
   - Add your Android/iOS app to the project.
   - Download `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) and place them in their respective directories.

4. **Run the app**
   ```bash
   flutter run
   ```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

