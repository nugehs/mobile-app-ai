# Event Ticketing Mobile App

A React Native Expo application for event organizers to manage events and check in guests.

## Features

- Event organizer authentication
- Event management
- Guest list management
- QR code scanner for check-ins
- Offline support
- Profile management

## Setup

1. Install dependencies:
```bash
yarn install
```

2. Run the app:
```bash
yarn start
```

## Project Structure

```
src/
├── components/    # Reusable UI components
├── screens/       # Screen components
├── navigation/    # Navigation configuration
├── services/     # API and other services
├── store/        # Redux store and slices
└── types/        # TypeScript type definitions
```

## Technology Stack

- React Native with Expo
- TypeScript
- Redux Toolkit for state management
- React Navigation v6
- Expo Secure Store
- Expo Barcode Scanner