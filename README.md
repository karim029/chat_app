
# Flutter Chat App

A Flutter-based chat application demonstrating various features and functionalities.

## Features

- **User Authentication**: Secure login and signup using Firebase Authentication.
- **Real-time Messaging**: Send and receive messages instantly using Firebase Firestore.
- **Profile Management**: Users can update their profile information.
- **Media Sharing**: Share images and files within the chat.
- **Push Notifications**: Receive notifications for new messages.

## Skills Demonstrated

- **Flutter Development**: Built a cross-platform mobile application using Dart and Flutter.
- **Firebase Integration**: Utilized Firebase for authentication, real-time database, and cloud storage.
- **State Management**: Managed application state using Provider for better performance and scalability.
- **Asynchronous Programming**: Implemented async and await for handling asynchronous operations smoothly.
- **UI/UX Design**: Designed a responsive and intuitive user interface.

## Getting Started

### Prerequisites

- [Flutter](https://flutter.dev/docs/get-started/install) installed on your machine.
- A Firebase project set up with Firestore and Authentication enabled.

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/karim029/chat_app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd chat_app
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```
4. Configure Firebase:
   - Follow the instructions to add your `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) files.

### Running the App

Run the app on an emulator or a physical device:
```sh
flutter run
```

## Folder Structure

- **lib**: Contains the main Flutter application code.
  - **screens**: All the UI screens of the application.
  - **widgets**: Reusable widgets.
  - **services**: Firebase service integrations.
  - **models**: Data models used in the app.
- **assets**: Static assets like images.
- **functions**: Cloud functions for additional backend logic.
- **test**: Unit and widget tests.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
