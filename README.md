# Course Registration Portal

A comprehensive mobile application built with Kotlin for managing school course registrations, featuring integrated payment processing, automated enrollment systems, and bulk data management capabilities.

## Features

### 💳 Integrated Payment Gateway
- **ZaloPay Integration**: Secure payment processing for course registration fees
- **Real-time Payment Verification**: Instant transaction confirmation and status updates
- **Secure Transaction Processing**: End-to-end encryption for financial data protection

### Automated Course Enrollment System
- **Schedule Conflict Detection**: Automatically prevents overlapping class registrations
- **Prerequisite Validation**: Ensures students meet course requirements before enrollment
- **Capacity Management**: Real-time tracking of available seats across multiple semesters
- **Multi-semester Support**: Handles course planning for current and future terms

### Bulk Data Processing
- **High-volume Processing**: Handle up to **100 records simultaneously**
- **Excel File Support**: Import/export functionality for:
  - Student records
  - Grade management
  - Class rosters
- **Data Validation**: Comprehensive error checking and data integrity verification
- **Batch Operations**: Streamlined bulk updates for administrative efficiency

## Technology Stack

- **Language**: Kotlin
- **Platform**: Android Mobile
- **Payment**: ZaloPay SDK
- **File Processing**: Excel handling capabilities
- **Architecture**: Modern Android development practices

## Installation

### Prerequisites
- Android Studio Arctic Fox or later
- Kotlin 1.5+
- Android SDK API level 21+
- ZaloPay merchant account for payment integration

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/mainhatnam219/_underscore.portalProject.git
   cd _underscore.portalProject
   ```

2. Open the project in Android Studio

3. Configure ZaloPay integration:
   - Add your ZaloPay API keys to `local.properties`
   - Update payment configuration in the app module

4. Build and run the application

## Usage

### For Students
1. **Browse Courses**: View available courses with detailed information
2. **Check Prerequisites**: Verify eligibility before registration
3. **Register for Courses**: Select desired courses with automatic conflict detection
4. **Make Payments**: Secure payment processing through ZaloPay
5. **Track Enrollment**: Monitor registration status and payment confirmation

### For Administrators
1. **Bulk Data Import**: Upload student records and course data via Excel files
2. **Manage Capacity**: Set and monitor course enrollment limits
3. **Process Payments**: Track and verify payment transactions
4. **Generate Reports**: Export enrollment data and class rosters

## 🏗Architecture

The application follows modern Android architecture principles:

- **MVVM Pattern**: Clear separation of concerns with ViewModels and LiveData
- **Repository Pattern**: Centralized data management
- **Dependency Injection**: Modular and testable code structure
- **Coroutines**: Asynchronous programming for smooth user experience


## Testing

Run the test suite:
```bash
./gradlew test
./gradlew connectedAndroidTest
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors

- **mainhatnam219** - *Initial work* - [GitHub Profile](https://github.com/mainhatnam219)

## Support

For support and questions:
- Create an issue in this repository
- Contact: mainhatnam01@gmail.com
---
