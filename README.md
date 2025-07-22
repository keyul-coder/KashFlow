# KashFlow - Point of Sale System
KashFlow is a POS (Point of Sale) system built with React. 


A modern React Native mobile application built with Expo for managing convenience store operations, including inventory management, sales processing, report Graph and employee management .

## 📱 Features

### Core Functionality
- **Point of Sale System** - Process customer transactions with barcode scanning
- **Inventory Management** - Track stock levels, add/edit products, and manage restocking
- **Sales Reporting** - Generate detailed sales reports and analytics
- **User Authentication** - Secure login/logout with role-based access control
- **Employee Management** - Manage staff with different permission levels (Cashier, Manager, Admin)

### Advanced Features
- **Real-time Notifications** - Stay updated with low stock alerts and system notifications
- **PDF Export** - Generate and print receipts and reports
- **Data Persistence** - All data saved locally with Firebase database
- **Responsive Design** - Optimized for various screen sizes
- **Swipe Gestures** - Intuitive swipe-to-delete functionality

## 🛠️ Technology Stack

- **Framework**: React Native with Expo
- **Database**: Firebase 
- **State Management**: React Context API with Hooks
- **Authentication**: Custom implementation with AsyncStorage
- **UI Components**: React Native Elements
- **Navigation**: React Navigation
- **Additional Libraries**:
  - expo-print (PDF generation)
  - expo-barcode-scanner (Barcode scanning)
  - expo-notifications (Push notifications)

## 📋 Requirements Compliance

This application meets all specified requirements:

✅ **React Native through EXPO** - Built using Expo framework  
✅ **Hooks Implementation** - Extensive use of useState, useEffect, and custom hooks  
✅ **External Database** - SQLite database for data persistence  
✅ **Authentication Process** - Complete login/logout/signup system  
✅ **Problem Solving** - Addresses real-world POS system needs  
✅ **Data Persistence** - User data persists across sessions  
✅ **Code Availability** - Full source code available for review  


## 👥 User Roles & Access

### Admin
- Full system access
- User management
- System configuration
- All reporting features

### Manager  
- Inventory management
- Sales reporting
- Employee oversight
- Transaction processing

### Cashier
- Point of sale operations
- Basic inventory viewing
- Customer transactions

## 📊 Database Schema

The application uses SQLite with the following main tables:

- **users** - User authentication and profile data
- **inventory** - Product information and stock levels
- **transactions** - Sales transaction records
- **notifications** - System notifications and alerts


## 🔐 Authentication

The app includes a complete authentication system:

- **Sign Up**: Create new user accounts with email/password
- **Sign In**: Secure login with credential validation  
- **Sign Out**: Safe logout with session cleanup
- **Session Management**: Automatic session persistence

Default admin credentials for testing:
- Email: admin@convenipos.com
- Password: admin123

## 📱 Key Screens

1. **Sign In Screen** - User authentication
2. **POS Screen** - Main transaction processing
3. **Inventory Screen** - Product management
4. **Reports Screen** - Sales analytics
5. **Profile Screen** - User account management
6. **Notifications Screen** - System alerts
7. **Sigh IN and Out Screen** - User Signin and Sigh out

## 🧪 Testing

To test the application:

1. Start with the default admin account
2. Create additional user accounts with different roles
3. Add inventory items
4. Process sample transactions
5. Generate reports
6. Test notification system

## 🤝 Contributing with Team

1. Keyul patel
2. Smit Patel
3. Krina patel

##  Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Expo CLI
- Expo Go app (for testing on device)

### Installation

1. **Clone the repository**
   ```bash
   git clone [your-repository-url]
   cd convenipos
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**
   ```bash
   expo start
   ```

4. **Run on device/simulator**
   - Scan QR code with Expo Go app (mobile)
   - Press 'i' for iOS simulator
   - Press 'a' for Android emulator



**Built with ❤️ using React Native and Expo**