# React Native AI-Translate

This project is a versatile translation app built with **React Native Expo**. It leverages the **OpenAI API** to translate text, speech, and images. **Clerk** is integrated for user management, allowing users to log in, view their translation history, and manage their profile information.

## 🚀 Features

- **Text, speech, and image translation**: Powered by the OpenAI API for fast and accurate translations.
- **User management**: Clerk integration enables secure user authentication and profile management.
- **Translation history**: Users can view and access their past translations.
- **Fast and reliable**: Zustand and MMKV ensure performant state management and efficient data storage.

## 🛠️ Technologies Used

- **Expo**: Simplifies the development and execution of the React Native application.
- **Expo Router**: Provides file-based routing for React Native apps, simplifying navigation.
- **Reanimated**: A performant animation library for creating fluid and smooth animations.
- **OpenAI API**: Handles text, speech, and image translation.
- **Clerk**: User authentication and management system.
- **Zustand**: Lightweight and efficient state management library.
- **MMKV**: Fast and reliable data storage solution.

## 🔧 Installation and Usage

To run the project on your local machine, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/Alex3584/ai-translate.git
cd react-native-translate-app
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Configure Clerk and OpenAI Keys

- Obtain your API keys from the Clerk dashboard and OpenAI.
- Create a `.env` file in the root directory and add the following:

```env
CLERK_API_KEY=your_clerk_api_key
OPENAI_API_KEY=your_openai_api_key
```

### 4. App Setup

To build the app, perform the following steps:

3. Run `npx expo prebuild`
4. Run `npx expo run:ios` or `npx expo run:android`

Open the app on your physical device or emulator using the development build.
