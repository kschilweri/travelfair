# TravelFair

## Purpose
TravelFair is an Android application created as part of the D308 Mobile Application (Android) course in my Software Engineering degree. The app allows users to plan vacations by adding vacation details, including start and end dates, and any associated excursions. All data is stored locally on the device. The app is developed using Android Studio with Java as the backend.

---

## Features & How to Operate

### 1. Login Screen
- A Login Screen appears when the app is launched.
- Enter the following credentials to access the app:
    - **Username**: test
    - **Password**: test1234 

### 2. Main Vacation List
- Upon launching the app, enter the main vacation list screen by clicking the **red button** on the homepage.
- Add a vacation by tapping the **floating button** on the bottom of the vacation list screen.
- Use the **Search Bar** at the top of the vacation list screen to filter vacations by title. Typing a query will display only vacations starting with the query text.

### 3. Add Vacation Screen
- Fill in the following fields:
    - **Vacation Title**
    - **Hotel Name**
    - **Start Date** (via date picker)
    - **End Date** (via date picker)
- Ensure the **end date is after the start date** (validation provided).
- Save the vacation details to proceed.

### 4. Vacation Management
- Add excursions to a saved vacation by navigating to the detailed vacation view.
- Deleting a vacation requires prior deletion of its associated excursions.
- Use the **Notify Vacation** option to set up notifications for:
    - The vacation's starting day.
    - The vacation's ending day.
    - Notifications display the vacation title and whether it is starting or ending.
- Use the **Share** option to open the Android share menu, allowing you to copy vacation details to the clipboard, or share via email, messages, and other sharing options.

### 5. Add Excursion
- On the vacation details screen, tap the **floating button** at the bottom to navigate to the excursion add screen.
- Enter:
    - **Excursion Title**
    - **Excursion Date** (must fall within the vacation dates).

### 6. Excursion Management
- Excursions are directly associated with their parent vacation through a foreign key (`vacation_id`).
- Adding an excursion outside the vacation dates will prompt a **toast notification** and prevent saving.
- Delete an excursion via the **menu (three dots)** on the top-right corner of the screen.
    - Confirm deletion through the dialog box.
- The Notify option will set a notification for the excursion day, displaying the excursion title.

---

## Android Version Information
- **Compiled SDK Version**: 34
- **Minimum SDK Version**: 26 (Android 8.0 Oreo)
- **Target SDK Version**: 34 (Android 14)

---

## APK Details
- **Version Code**: 1
- **Version Name**: 1.0

---


