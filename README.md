## Prerequisites
- **Node.js and npm**: Install from [Node.js website](https://nodejs.org/).
- **Expo CLI**: Install globally using npm:
  ```bash
  npm install -g expo-cli
  ```

## Getting Started
1. **Clone this repository to your local machine**:
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the project directory**:
   ```bash
   cd ride-hailing-app
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Create a Firebase project**:
   - Go to the [Firebase Console](https://console.firebase.google.com/).
   - Click on "Add project" and follow the instructions to set up your project.
   - Once your project is created, click on "Web" to add Firebase to your web app.
   - Copy the Firebase configuration object.

5. **Configure Firebase in your project**:
   - Create a file named `.env` in the project root directory.
   - Add your Firebase configuration to the `.env` file:
     ```plaintext
     FIREBASE_API_KEY=your-api-key
     FIREBASE_AUTH_DOMAIN=your-auth-domain
     FIREBASE_PROJECT_ID=your-project-id
     FIREBASE_STORAGE_BUCKET=your-storage-bucket
     FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
     FIREBASE_APP_ID=your-app-id
     ```

6. **Start the Expo development server**:
   ```bash
   npm start
