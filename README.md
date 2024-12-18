# Nearby App

This project was developed as part of a **mobile development course with React Native and Expo**, with the primary goal of learning the technology and developing a demo app in practice.

## Requirements

- **Node.js** installed on your machine
- **Android Emulator** or **iOS Simulator** (if you want to test locally)
- **Expo Go** installed on your smartphone (to test live on your device)

## Project Structure

The repository contains two main folders:

1. **`api`**: Contains the API developed with **Node.js** and **Prisma**, which provides the data used by the app.
2. **`nearby`**: Contains the app developed with **React Native** and **Expo**.

## How to Run the Project

### 1. **Prepare the API**

First, navigate to the `api` folder and install the dependencies:

```bash
cd api
npm install
# or
yarn install
```

After installation, start the API:

```bash
npm start
# or
yarn start
```

The API will be running and ready to provide data for the app.

### 2. **Run the App**

Next, go to the nearby folder and install the app's dependencies:

```bash
cd ../nearby
npm install
# or
yarn install
```

To run the app, use the following command:

```bash
npm run start:dev
# or
yarn run start:dev
```

### 3. **Test the App**

- Emulator: Open an Android or iOS emulator on your machine, and the app will load automatically.
- On your smartphone: If you prefer testing on your device, install Expo Go and scan the QR code displayed in the terminal or the Expo development page.