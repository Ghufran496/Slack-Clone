# Slack Clone

A real-time messaging application inspired by Slack, built with modern web technologies.

![Slack Clone](https://cdn-icons-png.flaticon.com/512/2111/2111615.png)

## Overview

This Slack Clone is a fully-functional messaging application that mimics the core features of Slack. It allows users to:

- Sign in with Google Authentication
- Create and join channels
- Send and receive real-time messages
- View message history
- Toggle sidebar visibility for better mobile experience

## Tech Stack

### Frontend
- **React 17**: UI library for building the user interface
- **TypeScript**: For type-safe code
- **Redux Toolkit**: State management for the application
- **React Router v6**: For navigation and routing
- **Styled Components**: For component-scoped CSS styling
- **Material UI**: For UI components and icons
- **Luxon**: For date and time formatting

### Backend & Infrastructure
- **Firebase**: 
  - Firestore: Real-time NoSQL database for messages and channels
  - Authentication: Google sign-in integration
  - Hosting: For deployment

### Development Tools
- **Create React App**: Project bootstrapping and configuration
- **Prettier**: Code formatting

## Features

### Authentication
- Google Sign-In integration
- Session persistence

### Messaging
- Real-time message updates
- Message history with timestamps
- User avatars and names displayed with messages
- Auto-scroll to latest messages

### Channels
- Create new channels
- Join existing channels
- Channel details and information

### Responsive Design
- Collapsible sidebar for mobile view
- Responsive layout for all screen sizes

## Getting Started

### Prerequisites
- Node.js (v14 or higher recommended)
- npm or yarn

### Installation

1. Clone the repository
```
git clone https://github.com/yourusername/slack-clone.git
cd slack-clone
```

2. Install dependencies
```
npm install
```

3. Start the development server
```
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Build for Production

```
npm run build
```

This builds the app for production to the `build` folder, optimizing the build for the best performance.

## Project Structure

- `/src`: Source code
  - `/components`: React components
  - `/firebase`: Firebase configuration and utilities
  - `/redux`: Redux store and slices
  - `/hooks`: Custom React hooks

## Learn More

To learn more about the technologies used in this project:

- [React Documentation](https://reactjs.org/)
- [TypeScript Documentation](https://www.typescriptlang.org/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [Firebase Documentation](https://firebase.google.com/docs)
- [Styled Components](https://styled-components.com/)
- [Material UI](https://mui.com/)
