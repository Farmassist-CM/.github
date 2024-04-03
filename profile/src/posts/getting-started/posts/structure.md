---
title: "Structure"
summary: "Here we shall enphasise on the main mobile app folder structure"
eleventyNavigation:
  key: Structure
  parent: Getting Started
  order: 3
---

Farmassist utilizes a modular architecture pattern to separate concerns and promote code reuse:

Presentation Layer: Responsible for rendering UI components and managing user interactions.
Data Layer: Handles data retrieval, storage, and manipulation, interacting with external APIs and storage solutions.
Business Logic Layer: Implements business rules and processes, orchestrating interactions between the presentation and data layers.
Integration Layer: Facilitates communication with external services and libraries, such as Expo APIs and third-party packages.

## Main Mobile App Folder Structure

The folder structure of the React Native Expo version of Farmassist is organized to align with the project architecture and streamline development:

### Tree view 📂

```html

Farmassist-Mobile/
├─ app/
│  ├─ components/
│  ├─ config/
│  ├─ constants/
│  ├─ hooks/
│  ├─ navigation/
│  ├─ screens/
│  ├─ services/
│  ├─ stores/
├─ assets/
│  ├─ fonts/
│  ├─ images/
App.tsx

```

#### `app/`

This directory contains the core application logic and functionality.

- **`components/`:** Contains reusable UI components used across multiple screens, promoting code reusability and consistency.

- **`config/`:** Holds configuration files and settings related to the application, such as API endpoints, environment variables, and third-party integrations.

- **`constants/`:** Defines constant values used throughout the application, such as error messages, theme colors, and app-wide configurations.

- **`hooks/`:** Contains custom React hooks used to encapsulate logic and functionality for reuse across components.

- **`navigation/`:** Manages navigation logic and routing between screens using a navigation library like React Navigation.

- **`screens/`:** Houses screen components representing different sections of the application, such as home, settings, farm management, and disease detection.

- **`services/`:** Manages service classes responsible for handling external services and APIs, such as weather data retrieval and news updates.

- **`stores/`:** Contains files related to state management, such as Redux stores, actions, reducers, and selectors, facilitating centralized state management across the application.

#### `assets/`

This directory contains static assets used in the application, such as fonts, images, and other resources.

- **`fonts/`:** Stores font files used for text styling and typography within the application.

- **`images/`:** Holds image files used for graphical elements, illustrations, and other visual components within the application.

#### `App.tsx`

This is the main entry point of the application, where the main components are initialized and configured. It serves as the starting point for rendering the application UI and managing its lifecycle.
