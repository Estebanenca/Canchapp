# Canchapp

## Project Overview
Canchapp is a sports field booking application designed to streamline the process of booking sports facilities. Users can view available fields, make reservations, and manage their bookings seamlessly through a mobile app.

## Technology Stack
- **Frontend:** React Native
- **Backend:** NestJS
- **Database:** PostgreSQL
- **Authentication:** JWT & OAuth2
- **Deployment:** Docker, AWS

## Setup Instructions
### Backend Setup
1. Clone the repository: `git clone https://github.com/Estebanenca/Canchapp.git`
2. Navigate to the backend directory: `cd backend`
3. Install dependencies: `npm install`
4. Create a `.env` file and fill in the required environment variables.
5. Run migrations: `npm run migrate`
6. Start the backend server: `npm run start`

### Mobile Setup
1. Navigate to the mobile directory: `cd mobile`
2. Install dependencies: `npm install`
3. Start the React Native packager: `npm start`
4. Run the application on an emulator or physical device:
   - For Android: `npx react-native run-android`
   - For iOS: `npx react-native run-ios`

## Folder Structure
```
Canchapp/
├── backend/
│   ├── src/
│   │   ├── modules/    # Contains API modules
│   │   ├── config/     # Configuration files
│   │   └── main.ts     # Entry point for the NestJS application
│   ├── package.json
├── mobile/
│   ├── src/
│   │   ├── components/ # Reusable components
│   │   ├── screens/     # Application screens
│   │   └── App.js       # Main application file
│   ├── package.json
└── README.md
```

## Development Guidelines
- Follow the coding standards adopted by the project.
- Write clear and concise commit messages.
- Branch naming convention: feature/[feature_name], bugfix/[fix_name].
- Ensure to run tests before making a pull request.
- Document any significant changes made to the codebase.

---
Please refer to the official documentation for any additional setups or configurations needed.