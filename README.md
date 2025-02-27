Simple Android App with Top and Bottom App Bar
This project demonstrates how to implement a standard navigation layout in an Android application with a Top App Bar (Toolbar) and a Bottom App Bar. The app displays a simple "Welcome to the App" message in the center of the screen.

Features
Top App Bar: Displays the application name on the left and a search icon on the right.
Bottom App Bar: Contains a centered Floating Action Button (FAB), with two action items: a menu icon on the left and a profile icon on the right.
Main Content: Displays a simple TextView with the message "Welcome to the App".
Requirements
Android Studio
Android SDK
Minimum SDK version: API 21 (Lollipop)
Setup
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/simple-android-app.git
Open the project in Android Studio:

Open Android Studio and select "Open an existing project".
Navigate to the project directory and open it.
Run the app:

Select a device or emulator from the available options in Android Studio.
Press the Run button to install and launch the app on the selected device/emulator.
Project Structure
activity_main.xml: Contains the layout for the Main Activity, including the Top App Bar, Bottom App Bar, and the main content.
MainActivity.java: Contains the logic to set up the Toolbar and BottomAppBar, and handle user interactions with the Floating Action Button (FAB).
Customization
Top App Bar: You can change the app name by modifying the android:title attribute in the Toolbar element.
Floating Action Button: Modify the android:srcCompat attribute of the FloatingActionButton to use a custom icon.
Icons: You can replace the ic_menu and ic_add icons with your own custom icons in the res/drawable folder.
Menu Items: Add your menu items in the res/menu directory and handle them in the activity.
Libraries Used
Material Components for Android: To implement the BottomAppBar and FloatingActionButton.
License
This project is licensed under the MIT License - see the LICENSE file for details.
