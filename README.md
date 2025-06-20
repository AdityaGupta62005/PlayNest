# PlayNest - Turf Booking Android App

PlayNest is a comprehensive Android application for booking sports turfs and facilities. The app provides a seamless experience for users to discover, book, and manage turf reservations while offering turf owners powerful management tools.

## 🏆 Features

### For Users
- **Browse Turfs**: Discover available sports facilities with detailed information
- **Time Slot Booking**: View and book available time slots for various sports
- **Multiple Sports Support**: Football, Cricket, Basketball, Tennis, Badminton, Swimming, and more
- **Booking Management**: Track your current and past bookings
- **Player Requests**: Request additional players for your bookings
- **Notifications**: Stay updated with booking confirmations and player requests
- **User Profiles**: Manage your personal information and preferences

### For Turf Owners
- **Dashboard**: Overview of bookings, revenue, and statistics
- **Turf Management**: Add, edit, and manage multiple turf facilities
- **Booking Analytics**: Detailed statistics and revenue tracking
- **Notifications**: Real-time updates on new bookings and reviews
- **Review Management**: Monitor and respond to customer feedback

## 🛠️ Technology Stack

- **Language**: Java
- **Platform**: Android (API Level 21+)
- **Architecture**: MVVM (Model-View-ViewModel)
- **Backend**: Firebase (Authentication, Firestore, Storage)
- **UI Components**: Material Design Components
- **Navigation**: Android Navigation Component
- **Charts**: MPAndroidChart for analytics
- **Image Loading**: Glide

## 📱 Screenshots

*COMMING SOON*

## 🚀 Getting Started

### Prerequisites

- Android Studio Arctic Fox or later
- JDK 8 or higher
- Android SDK API Level 21 or higher
- Firebase project setup

### Installation

1. **Clone the repository**
   \`\`\`bash
   git clone https://github.com/yourusername/playnest-turf-booking.git
   cd playnest-turf-booking
   \`\`\`

2. **Open in Android Studio**
   - Launch Android Studio
   - Select "Open an existing Android Studio project"
   - Navigate to the cloned directory and select it

3. **Firebase Setup**
   - Create a new Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Add your Android app to the Firebase project
   - Download the `google-services.json` file
   - Place it in the `app/` directory
   - Enable Authentication, Firestore, and Storage in Firebase Console

4. **Build and Run**
   - Sync the project with Gradle files
   - Build the project
   - Run on an emulator or physical device

### Configuration

1. **Firebase Configuration**
   - Update Firebase security rules (see `firebase_security_rules.js`)
   - Configure authentication providers in Firebase Console
   - Set up Firestore database structure

2. **App Configuration**
   - Update package name in `AndroidManifest.xml` if needed
   - Configure app colors in `res/values/colors.xml`
   - Update app name and strings in `res/values/strings.xml`

## 📁 Project Structure

\`\`\`
app/
├── src/main/java/com/example/playnest/
│   ├── data/
│   │   ├── model/          # Data models
│   │   ├── repository/     # Repository pattern implementation
│   │   └── remote/         # Firebase data sources
│   ├── presentation/
│   │   ├── auth/           # Authentication screens
│   │   ├── booking/        # Booking related screens
│   │   ├── home/           # Home screen
│   │   ├── notifications/  # Notifications
│   │   ├── owner/          # Owner dashboard screens
│   │   └── profile/        # User profile
│   └── utils/              # Utility classes
├── res/
│   ├── drawable/           # Icons and images
│   ├── layout/             # XML layouts
│   ├── menu/               # Menu resources
│   ├── navigation/         # Navigation graphs
│   └── values/             # Colors, strings, styles
└── AndroidManifest.xml
\`\`\`

## 🔧 Key Components

### Data Models
- **User**: User information and authentication
- **Turf**: Sports facility information
- **TimeSlot**: Available booking slots
- **Booking**: Booking details and status
- **Notification**: User notifications
- **Sport**: Supported sports categories

### Repositories
- **AuthRepository**: User authentication management
- **BookingRepository**: Booking operations
- **UserRepository**: User data management
- **TurfRepository**: Turf information management

### ViewModels
- **AuthViewModel**: Authentication state management
- **BookingViewModel**: Booking operations
- **OwnerTurfViewModel**: Owner turf management

## 🎨 UI/UX Features

- **Material Design**: Modern and intuitive interface
- **Bottom Navigation**: Easy navigation between main sections
- **Responsive Design**: Optimized for different screen sizes
- **Dark Theme Support**: Comfortable viewing in low light
- **Smooth Animations**: Enhanced user experience
- **Loading States**: Clear feedback during operations

## 🔐 Security Features

- **Firebase Authentication**: Secure user authentication
- **Data Validation**: Input validation and sanitization
- **Role-based Access**: Different permissions for users and owners
- **Secure API Calls**: Protected backend communications

## 📊 Analytics & Monitoring

- **Booking Statistics**: Revenue and booking analytics
- **User Engagement**: Track user interactions
- **Performance Monitoring**: App performance metrics
- **Crash Reporting**: Automatic crash detection and reporting

## 🧪 Testing

### Running Tests
\`\`\`bash
# Unit tests
./gradlew test

# Instrumented tests
./gradlew connectedAndroidTest
\`\`\`

### Test Coverage
- Unit tests for ViewModels and Repositories
- UI tests for critical user flows
- Integration tests for Firebase operations

## 🚀 Deployment

### Debug Build
\`\`\`bash
./gradlew assembleDebug
\`\`\`

### Release Build
\`\`\`bash
./gradlew assembleRelease
\`\`\`

### Play Store Deployment
1. Generate signed APK/AAB
2. Update version code and name
3. Test on multiple devices
4. Upload to Google Play Console

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Coding Standards
- Follow Android development best practices
- Use meaningful variable and method names
- Add comments for complex logic
- Maintain consistent code formatting
- Write unit tests for new features

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Firebase for backend services
- Material Design for UI components
- MPAndroidChart for analytics visualization
- Glide for image loading
- Android Jetpack components

## 📈 Roadmap

### Version 2.0
- [ ] Real-time chat between players
- [ ] Payment gateway integration
- [ ] Advanced booking filters
- [ ] Social features and player matching
- [ ] Offline mode support

### Version 2.1
- [ ] AR facility preview
- [ ] Weather integration
- [ ] Tournament management
- [ ] Loyalty program
- [ ] Multi-language support

## 🔄 Changelog

### Version 1.0.0 (Current)
- Initial release
- Basic booking functionality
- User and owner dashboards
- Firebase integration
- Material Design UI

---

**Made with ❤️ for sports enthusiasts**
