# NexCo-Flutter-Supabase-Android-App
Nexco is a feature-rich and modern social media application built to connect people through secure and interactive digital spaces. It includes features like user authentication, posts, likes, comments, real-time chat, and more — offering a seamless social networking experience.

# 🔑 Key Features

📧 Email Authentication – Sign in securely with email and password
📲 OTP Verification – Login or register using mobile number and OTP (One-Time Password)
👤 Profile Management – Add and update name, profile photo, and bio
📝 Post Creation – Share thoughts with text and optional images
💬 Engage with Content – Like and comment on posts in real time
🌙 Modern Dark UI – Clean and responsive interface with dark theme

# 🛠️ Tech Stack

Frontend: Flutter (Dart)
Backend-as-a-Service: Supabase
Database: PostgreSQL (via Supabase)
Authentication: Supabase Auth (Email & OTP)
State Management: GetX
OTP UI Input: flutter_otp_text_field, pinput

# 📱 Screenshots
<img width="720" height="1506" alt="image" src="https://github.com/user-attachments/assets/5791f5e5-1e76-4fb9-85da-38ed7901befe" />
<img width="720" height="1514" alt="image" src="https://github.com/user-attachments/assets/426f54c2-ea2f-40b9-9f66-0bb815c8bd5e" />
<img width="720" height="1520" alt="image" src="https://github.com/user-attachments/assets/70ac0956-17c4-47e7-90a6-794379d3f587" />

## 🔧 Setup Instructions

### ✅ Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- Android Studio / VS Code
- Supabase account ([Create here](https://supabase.io))

### 🔌 1. Clone the Repository

git clone https://github.com/yourusername/nexco.git
cd nexco

## Install Dependencies

flutter pub get

## Set Up Environment Variables

Replace ur Supabase url and supabase key in .env file in the root directory:

SUPABASE_URL=your-supabase-url
SUPABASE_ANON_KEY=your-supabase-anon-key

## Run the App

flutter run

## 📦 Dependencies Used
cupertino_icons: ^1.0.8
get: ^4.7.2
get_storage: ^2.1.1
form_validator: ^2.1.1
flutter_dotenv: ^5.2.1
supabase_flutter: ^2.9.0
image_picker: ^1.1.2
flutter_image_compress: ^2.4.0
uuid: ^4.5.1
pinput: ^3.0.0
flutter_otp_text_field: ^1.1.0+2
jiffy: ^6.4.3
intl: ^0.20.2

##🔐 Why Multi-Factor Authentication?
Instead of relying solely on passwords, NexCo implements:

✅ Email Verification – Ensures trusted access to the platform
✅ Phone Number OTP Login – Adds an extra layer of identity validation
This makes the app more secure and user-friendly, especially for mobile-first users.

##🌱 Future Enhancements

🔒 Biometric authentication (Fingerprint/Face ID)
💬 Real-time chat system
🔔 In-app and push notifications
🌐 iOS and web app support
🧑‍💻 Admin dashboard for user/content moderation

##👩‍💻 About the Developer

Hi, I'm K. Kavya sree, a Computer Science Engineering student at Rishi MS Institute of Engineering, Hyderabad.
This project is a practical implementation of what I’ve learned in mobile development, with a strong focus on user security and modern app architecture.

LinkedIn: linkedin.com/in/kavya-sree-katabathina-59a1731b3
GitHub: @Kavyasree2006
Email: katabathina1kavyasree@gmail.com

##📚 References

Supabase Documentation
Flutter Documentation
Dart Language Tour
PostgreSQL



