---
title: "Frequently Asked Questions"
summary: "Have some questions? You may find it here."
displaySummary: true
layout: "layouts/faq.html"
faqs:
-
    title: "Getting Started with Farmassist"
    items:
    -
        title: "What is Farmassist?"
        description: "Farmassist is a mobile application designed to empower farmers through the integration of Internet of Things (IoT) technology and Artificial Intelligence (AI). It provides features for farm management, real-time sensor data monitoring, and AI-powered plant disease detection."
    -
        title: "Is Farmassist free to use?"
        description: "The Farmassist app itself is free to download and use. However, some features, like receiving weather data specific to your farm location, may require additional subscriptions to external services (e.g., OpenWeather API). NOTE: the licence should be taken in consideration while interacting with the source code."
    -
        title: "What devices are compatible with Farmassist?"
        description: "Farmassist is currently available as an Android app. We're working on an iOS version, so stay tuned! To utilize the IoT monitoring features, you'll need compatible farm sensors that can connect to the internet and transmit data."
    -
        title: "Do you have a flutter version?"
        description: "Yes but it is depricated, so we shall wait for the community to grow and contribute to create an updated flutter"
-
    title: "Using Farmassist Features"
    items:
      -
        title: "How do I track my planting and harvesting data?"
        description: "Farmassist's farm management section allows you to record planting details like plant name, number planted, and estimated harvest date. You can also track harvesting data and mark crops as harvested."
      -
        title: "What kind of sensor data can I monitor?"
        description: "Farmassist can display real-time data from various farm sensors, including air humidity, air temperature, soil moisture, soil pH, and soil salinity. This data is presented visually through charts for easy analysis."
      -
        title: "How does the plant disease detection work?"
        description: "Farmassist utilizes a pre-trained AI model to analyze images captured through the app's camera. Simply take a picture of a potentially diseased plant, and the model will suggest potential disease types based on its analysis."
-
    title: "Technical Aspects"
    items:
      -
        title: "Is Farmassist open-source?"
        description: "Yes! Farmassist is open-source and available on GitHub under the GPLv3 license. This allows anyone to contribute to the project's development and make improvements."
      -
        title: "I'm a developer. How can I contribute to Farmassist?"
        description: "We welcome contributions from developers! The FAQ page on the GitHub repository provides detailed instructions on setting up your development environment and contributing code. You can also find links to relevant resources for working with Firebase and Cloud Functions."
      -
        title: "Can I train my own plant disease detection model?"
        description: "While Farmassist comes with a pre-trained model, you can certainly train your own using Google Cloud AutoML Vision. The FAQ page includes a link to the Edge Device Model Quickstart guide to help you get started."
---
