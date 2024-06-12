Erciyes University
Computer Engineering
Mobile Application Development
Assoc. Prof. Fehim Köylü

1030520974 Göktuğ Berkbaş

Mobile Application Development Weather App Project

Weather App

This Flutter project is a mobile application that visually presents weather data. The application uses an API to fetch various weather information and displays it in a user-friendly interface.

Getting Started

Clone the project to your computer or download it as a ZIP file.
Open the terminal in the main directory of your Flutter project.
Run the command flutter pub get in the terminal to install dependencies.
Run the project in a Flutter development environment.
Project Structure and Contents

lib/screens/: Folder containing files for the application's screens.

home.dart: Main screen displaying popular categories and weather forecasts.

login.dart: User login screen allowing users to sign in and register.

search.dart: Search screen enabling users to search for weather information.

splash.dart: Start screen displayed while the application is loading.

lib/consent/: Folder containing commonly used components of the application.

appbar.dart: Component creating the top bar of the application.

colors.dart: File containing the color palette used.

navigation.dart: Component managing in-app navigation.

lib/services/: Folder containing files providing data processing and presentation services for the application.

notification_service.dart: File managing notification services.

weather_cubit.dart: Cubit class managing weather data.

weather_records.dart: File containing helper classes for processing weather records.

lib/models/: Folder containing data models used by the application.

condition_model.dart: Model class representing weather conditions.

current_model.dart: Model class representing current weather data.

day_model.dart: Model class representing daily weather data.

forecast_day_model.dart: Model class representing weather forecasts.

hour_model.dart: Model class representing hourly weather data.

location_model.dart: Model class representing location data.

lib/utils/: Folder containing files providing utility functions.

chart_data_formatter.dart: File containing helper classes for formatting chart data.

Used Libraries

flutter_local_notifications: Used for managing local notifications.

freezed_annotation: Used for code generation for serialization operations.

fl_chart: Used for creating and visualizing charts.

The purpose of this project is to create an example of fetching and displaying weather data using Flutter and various packages.

The application is designed to help users easily track weather forecasts and plan their daily lives.



