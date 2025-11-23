# 📱 New-Aqal-Owner-Demo

**Aqal** is a modern, robust Flutter application designed for [Insert brief description: e.g., Real Estate Management / Property Tracking / Financial Analytics]. Built with scalability and clean architecture in mind.

<div align="center">
  <img src="screenshots/demo.gif" width="250" />
  <br>
  <img src="screenshots/screen1.png" width="200" />
  <img src="screenshots/screen2.png" width="200" />
  <img src="screenshots/screen3.png" width="200" />
</div>

## ✨ Features

* **Secure Authentication:** Integration with secure storage for token management.
* **Real-time Analytics:** Interactive charts and data visualization using `fl_chart`.
* **Push Notifications:** Integrated Firebase Messaging for real-time updates.
* **Document Management:** Upload files, pick images, and generate/view PDFs.
* **Responsive Design:** Adapts to various screen sizes using `flutter_screenutil`.

## 🛠 Tech Stack

This project utilizes a modern Flutter tech stack focusing on maintainability and code generation.

### Architecture & State Management
* **State Management:** [Flutter Bloc](https://pub.dev/packages/flutter_bloc) (Cubit pattern)
* **Dependency Injection:** [GetIt](https://pub.dev/packages/get_it)
* **Data Class Generation:** [Freezed](https://pub.dev/packages/freezed) & [JsonSerializable](https://pub.dev/packages/json_serializable)

### Networking & API
* **Client:** [Dio](https://pub.dev/packages/dio) with [Pretty Dio Logger](https://pub.dev/packages/pretty_dio_logger)
* **Type-safe HTTP Client:** [Retrofit](https://pub.dev/packages/retrofit)

### UI/UX
* **Design System:** Custom fonts (Inter) & Shimmer effects
* **Charts:** [FL Chart](https://pub.dev/packages/fl_chart)
* **Animations:** [Lottie](https://pub.dev/packages/lottie)
* **Responsiveness:** [Flutter ScreenUtil](https://pub.dev/packages/flutter_screenutil)

### Local Storage & caching
* **Secure Storage:** [Flutter Secure Storage](https://pub.dev/packages/flutter_secure_storage)
* **Shared Preferences:** [Shared Preferences](https://pub.dev/packages/shared_preferences)

### Integrations
* **Firebase:** Core & Messaging
* **File Handling:** File Picker, Image Picker, Open File, PDF
* **Notifications:** Flutter Local Notifications





---

Developed with ❤️ by [Your Name]
