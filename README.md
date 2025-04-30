# SmartFab Inventory App

A Flutter-based Material Tracking & Costing App for SmartFab Industries.

## Features

- **Role-Based Access Control**: Different interfaces for admins and operators
- **Real-time Material Tracking**: Track materials using QR/barcode scanning
- **Automated Cost Calculations**: Calculate product costs based on material consumption
- **Offline Functionality**: Work with the app even without internet connectivity
- **Reporting**: Generate PDF and CSV reports for inventory, consumption, and product costing

## Getting Started

### Prerequisites

- Flutter SDK
- Firebase account
- Android Studio / VS Code with Flutter extensions

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd smartfab_inventory_app
   ```

3. Install dependencies:
   ```
   flutter pub get
   ```

4. Configure Firebase:
   - Create a new Firebase project
   - Add Android and iOS apps to your Firebase project
   - Download and add the `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) files
   - Enable Firestore and Authentication in Firebase console

5. Run the app:
   ```
   flutter run
   ```

## Architecture

The app follows a provider-based architecture with the following components:

- **Models**: Data classes for User, Material, Process, Product, and Consumption
- **Services**: Authentication, Database, Scanner, and Report services
- **Screens**: UI components for different user interactions
- **Providers**: State management for different parts of the app

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
