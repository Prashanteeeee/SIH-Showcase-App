SnapSpot Showcase App
A professional-grade showcase application built with React Native and Expo, demonstrating a complete authentication flow and advanced native features like GPS location and in-app camera.

This project was built as a proof-of-concept to showcase the skills required for a high-stakes hackathon, focusing on clean code, modern UI/UX, and robust, real-world functionality.

✨ Core Features
This is not just a simple UI. This app includes a full suite of features that are essential for any modern mobile application.

🎨 Professional UI/UX: A beautiful, modern, dark-themed user interface designed for an intuitive and enjoyable user experience.

🔐 Full Authentication Flow:

Secure Signup: With robust client-side validation for name, email format, and password strength.

Persistent Login: User data is securely stored on the device using @react-native-async-storage/async-storage.

🧠 Smart Navigation with Expo Router:

AsyncStorage-Based Refresh: On app startup, a loading screen is shown while the app checks for a stored login session.

Protected Routes: Users are automatically directed to the Dashboard if logged in, or to the Login screen if not. This is a key feature for a professional app.

📍 Real-Time Location Services:

Permission Handling: Gracefully requests permission to access the device's location.

Reverse Geocoding: Converts the user's raw GPS coordinates into a full, human-readable street address.

📸 In-App Camera & Image Picker:

Professional UX: A single, clean button presents the user with a native pop-up menu to choose between the camera or the gallery.

Custom In-App Camera: Uses expo-camera to create a beautiful, full-screen camera experience inside the app, rather than relying on the default device camera.

Image Preview: Selected or captured images are beautifully displayed on the dashboard.

🧹 Clean, Professional Codebase:

TypeScript: The entire project is written in TypeScript for robust, error-free code.

Custom Hooks: All complex feature logic (for authentication, location, and image picking) is separated from the UI into reusable custom hooks, which is a senior developer best practice.

Organized Structure: The project uses a professional src folder structure to keep code clean, organized, and scalable.

🚀 Tech Stack
This project is built with a modern, professional, and efficient tech stack.

Framework: React Native (with Expo)

Language: TypeScript

Navigation: Expo Router (File-Based Routing)

Local Storage: @react-native-async-storage/async-storage

Native Features:

expo-location (for GPS and Reverse Geocoding)

expo-camera (for the in-app camera)

expo-image-picker (for the image gallery)

UI & Styling: React Native StyleSheet, react-native-vector-icons

🛠️ How to Run This Project
To run this project locally, follow these steps:

Clone the repository:

git clone [https://github.com/your-username/SnapSpot-Showcase-App.git](https://github.com/your-username/SnapSpot-Showcase-App.git)

Navigate to the project directory:

cd SnapSpot-Showcase-App

Install dependencies:

npm install

Run the application:

npx expo start
