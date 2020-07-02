
# TURN ON THE ISSUE TRACKER !!!!

Sorry for the yelling, but there are issues that could and should be raised and
discussed. For example:
  - The use of Google SafetyNet and subseqent tokens - that may be reasonable but the frequency with which tokens are re-freshed etc could lead to those being  a better tracker than IP addresses
  - The inclusion of the number of notifications (a bit of medical info) in the metrics (what should be a bit of devops info) seems entirely wrong to me.

# COVID Tracker Ireland


## Getting Started

Following these instructions will allow you to run and build the project on your local machine for development and testing purposes.

### Prerequisites

Follow the official guide "[Setting up the development environment](https://reactnative.dev/docs/environment-setup)" to set up your local machine to develop iOS and Android applications with React Native.

Install an xCode version that supports iOS 13.5, required by the [ExposureNotification framework](https://developer.apple.com/documentation/exposurenotification) used by the app.

Install `yarn` globally:

```bash
npm install -g yarn
```

For other installation methods, follow the official [Installation guide](https://classic.yarnpkg.com/en/docs/install).

### Installing

Clone this repository.

Install the npm dependencies:

```bash
yarn install
```

Create your `.env` file or copy it from the `.env.sample`:

```bash
cp .env.sample .env
```

Move to `ios/` folder and install the CocoaPods dependencies:

```bash
cd ios && pod install
```

## Running the applications locally

Start the React Native bundler:

```bash
yarn start
```

To start the Android application, run:

```bash
yarn android
```

To start the iOS one, run:

```bash
yarn ios
```
