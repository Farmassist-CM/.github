---
title: "Introduction"
summary: "Welcome to the official documentation of Farmassist."
eleventyNavigation:
  key: Introduction
  parent: Getting Started
  order: 1
---

Welcome to Farmassist! This comprehensive open-source project empowers farmers worldwide to leverage the power of data-driven insights and cutting-edge AI technology for a more sustainable and profitable agricultural future. This README provides a detailed overview of Farmassist's functionalities, architecture, and how you can contribute to its ongoing development.

## Farmassist: A Holistic Approach to Smart Farming

Farmassist is not just a mobile app; it's a comprehensive ecosystem designed to cater to all aspects of smart farming. Here's a glimpse of what Farmassist offers:

### Streamlined Farm Management

- **Track and Manage:** Easily track planting and harvesting data, access agricultural news updates, and make informed decisions about your crops.
- **Data Accessibility:** Access valuable agricultural news updates and make informed decisions about your crops.

### Real-Time Sensor Monitoring

- **Insights:** Gain valuable insights into environmental conditions with real-time data visualization of air humidity, soil moisture, temperature, pH, and salinity.
- **Integration:** Seamlessly integrate sensor data into your farm management system for better decision-making.

### AI-Powered Plant Disease Detection

- **Image Analysis:** Capture images of diseased plants and receive potential disease type suggestions using AI, both online and offline.
- **Accuracy:** Leverage AI algorithms for accurate disease detection and management.

### Predictive Farm Management (Future Implementation)

- **Optimization:** Utilize predictive algorithms to optimize planting and harvesting times, maximizing agricultural yield.
- **Efficiency:** Improve efficiency and productivity with predictive insights.

## Unveiling the Architecture

Farmassist is built on a robust foundation of Google Cloud services and powerful React native libraries. Let's delve into its core subsystems and the technologies that power them:

### 1. Farm Management Subsystem (Cloud Firestore)

- **Database:** Utilizes Cloud Firestore for efficient storage of farm management data like planting and harvesting details.
- **Functionality:** Enables users to track key information such as plant names, number planted, estimated harvest dates, and mark crops as harvested.
- **Integration:** Integrates with News API for fetching top headlines relevant to the agricultural sector.
- **Weather Data:** Optional integration with OpenWeather API for retrieving farm-specific weather data.

### 2. IoT Monitoring Subsystem (Firebase Realtime Database & Cloud Functions)

- **Real-Time Monitoring:** Employs Firebase Realtime Database as a central repository for real-time sensor data collected from IoT sensors.
- **Abnormality Detection:** Utilizes Cloud Functions to analyze sensor data for abnormal readings and trigger push notifications via Cloud Messaging to alert users.
- **Data Visualization:** Supports real-time data visualization through charts within the mobile app for better understanding of environmental conditions.

### 3. Plant Disease Detection Subsystem (Local AI Model & Cloud Image Recognition API)

- **Dual-Mode Approach:** Offers offline and online modes for plant disease detection.
  - **Offline Mode:** Uses a pre-trained AI model directly on the user's mobile device for analyzing captured images of diseased plants and suggesting potential disease types.
  - **Online Mode:** Utilizes a cloud-based image recognition API like Gemini Pro Vision or LLAva 2 for enhanced disease identification accuracy and specific disease classifications.

Farmassist provides a holistic solution for smart farming, combining streamlined farm management, real-time sensor monitoring, AI-powered disease detection, and predictive farm management capabilities, all built on a robust technological foundation, read more on [FAQ](/faq/) and [Changelog](/changelog/).

## History

This project has originally be thinked and implmented by [@Gilles MOMENI](https://github.com/menoc61), to help the population of low developed or developping counties to have a powerfull tool for the management of thier plantation. The agriculture sector in Cameroon contributed approximately **16.98%** to the country's GDP in 2022[[1]](https://tradingeconomics.com/cameroon/agriculture-value-added-percent-of-gdp-wb-data.html)[[2]](https://www.statista.com/statistics/446567/cameroon-gdp-distribution-across-economic-sectors/). This sector is a significant part of Cameroon's economy, engaging an estimated 70 percent of the economically active population[[3]](https://cameroon.panda.org/our_work/food_and_agriculture/).For the most accurate and up-to-date information, it's best to refer to official sources or organizations such as the World Bank [[4]](https://data.worldbank.org/indicator/NV.AGR.TOTL.ZS?locations=CM).

> Document source provided as `[1], [2], [3], [4]`. Please note that these figures are subject to change as new data becomes available. The researches was carried out the `03/04/2024, 2:52 AM`.

<img
  data-theme-mode
  alt="A minimalistic, low-level CSS framework"
  src="/img/cover/sprucecss.png"
  data-light-asset="/img/cover/sprucecss.png"
  data-dark-asset="/img/cover/sprucecss-light.png"
/>
