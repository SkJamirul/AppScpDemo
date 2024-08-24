# appscrip

The User Details App is a Flutter-based mobile application that 
fetches and displays a list of users from an API. Users can search for 
specific individuals using the search feature, refresh the list via pull-to-refresh,
and view detailed information about each user by tapping on a list item.
The app is designed with a clean and user-friendly interface, ensuring an enjoyable user experience.

## Features

User List: Displays a list of users fetched from an API.
Search Functionality: Allows users to search for a specific user by name.
Pull-to-Refresh: Users can refresh the list of users by pulling down.
User Details: Tapping on a user in the list navigates to a detailed view showing more information.

## How to Run the App

Flutter SDK: Ensure you have leatest Flutter sdk installed on your machine
Device or Emulator: A physical device or emulator to run the app.
 # Steps to Run
 1. Clone the Repository:
 2. Install Dependencies: "flutter pub get"
 3. Run the App: "flutter run"

## Assumptions and Decisions

API Response Handling: The app assumes that the API returns a valid and consistent response structure.
Any API errors are handled with toast notifications.

UI Design: The design prioritizes simplicity and ease of use, ensuring that the app is accessible and straightforward.

State Management: The app uses Bloc for state management, making it scalable and easy to maintain.

Search Implementation: The search functionality is implemented locally, filtering the list of users based on the user's input.

## Screenshots
![Screenshot_1724495942](https://github.com/user-attachments/assets/635cb3a9-462a-4e1c-a61f-1b98709a9a18)![WhatsApp Image 2024-08-24 at 17 59 28_3f3d6838](https://github.com/user-attachments/assets/b84ca301-7301-4202-b74b-fd3f498e7af5)



