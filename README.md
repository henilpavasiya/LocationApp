# Location App

A simple Android application demonstrating the usage of location services, using the Model-View-ViewModel (MVVM) architecture with Jetpack Compose for UI.

## Features

- Fetches and displays the user's current location.
- Reverse geocodes the latitude and longitude into a readable address.
- Handles location permission requests gracefully.
- Uses Google Play Services `FusedLocationProviderClient` for efficient location updates.

## Technologies Used

- **Kotlin**: Primary language for implementation.
- **Jetpack Compose**: Modern UI toolkit used for building native Android UI.
- **Google Play Services**: Utilized for accessing fused location services.
- **MVVM**: Architecture pattern separating concerns between UI, data, and business logic.

## Project Structure

- **MainActivity**: Hosts the main UI content using Compose.
- **LocationViewModel**: Manages the state and updates the location data for the UI.
- **LocationUtils**: Utility class for handling location permissions, requesting location updates, and reverse geocoding.


