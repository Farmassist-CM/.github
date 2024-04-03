---
title: "Setup"
summary: "We shall provide a dev setup and an installation setup for better enhancement with the app"
eleventyNavigation:
  key: Setup
  parent: Getting Started
  order: 4
---

For the ecosystem to run cuncurently you have to install servral different repositories for the proper functioning of the application. Each repository would have an individual readme for it's installation. Here we shall list out all the order on which you have to install them with a given description.

## clone the repository

Either clone or fork the project, if you need to clone it juste use the following command:

```shell
git clone https://github.com/Farmassist-CM/Farmassist-Mobile
```

## Install the dependencies

In the `package.json` file, you will find all of the dependencies (and scripts) to install them using the following command:

```shell
npm install
```

>Update `/app/config/config.base.ts` with your own configuration for firebase

## Run the development mode

To run the development mode, use the `npm script`.   This script will also watch for changes.

```shell
npm start
```

## Run the production mode

Before you go live, you should use the production script to compress the Sass files.

```shell
npm run build
```

> **Note** A CI/CD pipline would be created for you to download the apk file more easily.

## Additional Scripts

You can find some more npm scripts in the [package.json](https://github.com/Farmassist-CM/Farmassist-Mobile) that can be helpful.

## What if i want to fork the project?

Things to do if you want to fork or contribute to the project.

1. Refer to [Create a Firebase project and add config json to your desired build](https://rnfirebase.io/) (In our case we chosed android).
2. Refer to [Farmassist IoT Device Simulator](https://github.com/Farmassist-CM/farmassist-iot-device-simulator) to see how fake telemetery data can be sent to Realtime Database.
3. Refer to [Farmassist Firebase](https://github.com/Farmassist-CM/farmassist-firebase) for the Cloud Functions code that call Cloud Messaging service.
4. Refer to [Edge Device Model Quickstart](https://cloud.google.com/vision/automl/docs/edge-quickstart) if you want to train your own model for plant disease detection.
5. Refer to [CI/CD pipeline for React Native apps: use Fastlane and GitHub Actions](https://medium.com/@malikchohra/ci-cd-pipeline-for-react-native-apps-use-fastlane-and-github-actions-40f9ad2036d0) to set up a workflow that can release an APK for your android app whenever someone pushes the code to GitHub. Instead of using `push` event, I set up a manual trigger with `workflow_dispatch` event.
