
# teenteen™️ – Social Networking Super App

TeenTeen (aka *"teenteen"*) is a **modern revolutionary social networking super app** designed specifically for teenagers, offering a safe, engaging, and feature-rich platform for social interaction, content sharing, and community building. Built with cutting-edge technologies, TeenTeen (aka *"teenteen"*) provides a seamless experience across mobile devices while prioritizing user safety and privacy. 

---

## ✨ Features


- 🔑 Authentication (Login / Sign Up / Forgot Password)
- 🌍 Multilingual support (Indian + International languages)
- 📨 Real-time Messaging
- 👤 Profile Management
- 👥 GroupStudy: Study with your teen(s)
- ⚙️ Settings & Notifications
- 📱 Cross-platform (Android + iOS)
- 🔐 Secure with Firebase + JWT Auth
- 📊 Future-ready Super App Extensions

---
## 🛠 Tech Stack

### Frontend (Mobile App)

- Flutter: Cross-platform mobile development framework
- Dart: Programming language for Flutter
- Provider: State management solution
- Firebase Authentication: User authentication
- Firebase Cloud Firestore: NoSQL database
- Firebase Cloud Storage: File storage
- Firebase Cloud Messaging: Push notifications
- Socket.IO: Real-time communication
- Bloc: Business logic component for complex state management

### Backend


- Node.js: JavaScript runtime environment
- Express.js: Web application framework
- MongoDB: NoSQL database
- Redis: In-memory data structure store
- JWT: Authentication token management
- Socket.IO: Real-time bidirectional event-based communication
- AWS: Cloud hosting and services (EC2, S3, CloudFront)
- Docker: Containerization for deployment

---
### DevOps & Tools
- GitHub: Code repository and collaboration
- Postman: API testing
- Jira: Project management
- Figma: UI/UX design
- CircleCI: Continuous integration and deployment
- Firebase Hosting: Web app hosting
- Firebase Functions: Serverless backend functions
- Firebase Analytics: App analytics
- Firebase Crashlytics: Crash reporting
- Firebase Performance Monitoring: App performance monitoring
---
### 📦 Installation

Prerequisites:

- Node.js (v16 or higher)
- Flutter SDK (v3.0 or higher)
- MongoDB (v4.4 or higher)
- Redis (v6.0 or higher)
- Docker (optional for containerized deployment)
- Firebase CLI (for Firebase Hosting and Functions)

---

## 📂 Project Structure
   teenteen
   
            ├── android/
            ├── ios/
            ├── linux/
            ├── macos/
            ├── windows/
            ├── web/

            ├── assets/
               __ translations # .arb language files (multi-language support)
            ├── lib/
               __ main.dart # App entry point
               __ app_localizations.dart
               __ screens/ # UI Screens
               __ widgets/ # Reusable widgets
               __ services/ # Firebase / API services

            ├── backend/ # Node.js Backend (Express + Firebase Admin + MongoDB)
               __ server.js
               __ routes/
               
            ├── pubspec.yaml # Flutter dependencies
            ├── README.md

---   

## 🔧 Installation (packages)

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/teenteen.git
   cd teenteen
   ```

2. **Install Flutter dependencies**:
   ```bash
   flutter pub get
   ```

3. **Set up Firebase**:
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Add your Flutter app to the Firebase project.
   - Download the `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) files.
   - Place these files in the respective `android/app` and `ios/Runner` directories.

4. **Set up the backend**:
   - Navigate to the `backend` directory.
   - Install Node.js dependencies:
```bash
     npm install
```
   - Set up Firebase Admin SDK:
     - Download the Firebase Admin SDK JSON file from the Firebase Console.
     - Place the JSON file in the `backend` directory.
   - Set up MongoDB:
     - Create a MongoDB database and get the connection string.
     ---
## 🚀 Usage

1. **Running the Application**
   - Start the backend server:
     ```bash
     cd backend
     npm start
     ```
   - Launch the Flutter app on an emulator or physical device.
2. **Create an account or log in with existing credentials**
   - Open the app.
   - You will be prompted to create an account or log in with existing credentials.
   - Follow the on-screen instructions to complete the process.
---
## 🔄 Key Workflows

1. **User Registration**
   - Create a new account with your email and password.
   - Verify your email address to activate your account.
2. **Content Posting**
   - Share text, images, or videos with your teen(s).
   - Interact with other users by liking, commenting, or sharing posts.
3. **Group Interaction**
   - Join existing groups or create your own.
   - Participate in discussions, share ideas, and build a community.
4. **Direct Messaging**
   - Chat with your teen(s) individually or in groups.
   - Send messages, images, or videos to keep in touch.
5. **Event Management**
   - Create events and invite your teen(s) to join.
   - Manage RSVPs, track event RSVPs, and communicate with attendees.
   ---
## 🤝 Contributing

 We welcome contributions to the TeenTeen project! Please follow these guidelines:

## Development Process

- Fork the repository on GitHub.
- Create a feature branch:
  ```bash
  git checkout -b feature/amazing-feature
  ```
- Commit your changes:
  ```bash
  git commit -m 'Add amazing feature'
  ```
- Push to the branch:
  ```bash
  git push origin feature/amazing-feature
  ```
- Open a Pull Request

---
## Code Style
- Follow the official Flutter and Node.js style guides
- Write meaningful commit messages
- Ensure all tests pass before submitting
- Update documentation as needed

## Reporting Issues
Use the GitHub Issues page to report bugs or request features. Please include:

- Clear description of the issue
- Steps to reproduce
- Expected behavior
- Screenshots (if applicable)
- Browser/Device information (if applicable)
- Any other relevant details
---
## 📜 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/KremMitra/teenteen/blob/main/License) file for details.

---
## 📞 Contact

TeenTeen Development Team

- Email:   [contact@teenteen.app]([contact@teenteen.app)
- Website: [www.teenteen.app](www.teenteen.app)
- Twitter: [@TeenTeenApp]()
- TeenTeen: [Join our community]()
---


## 🙏 Acknowledgments

- Flutter and Node.js communities for their excellent tools and frameworks
- Our beta testers for valuable feedback
- Parents and educators who helped shape our safety features
- Open source contributors whose libraries power our application

---
