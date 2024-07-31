# Expense-Tracker-IOS-Android

<img width="230" alt="Screenshot 2024-07-30 at 4 08 09 PM" src="https://github.com/user-attachments/assets/09ef110f-15c2-4f38-86ef-8a0a5a30e3e1">
<img width="224" alt="Screenshot 2024-07-30 at 4 09 26 PM" src="https://github.com/user-attachments/assets/a3b8d826-e002-40be-8f03-0acdeca04544">




This Flutter Expense Tracker is a mobile application designed to help users manage and track their expenses efficiently. It leverages Flutter's powerful UI toolkit to provide a smooth and visually appealing user experience. The app allows users to add, view, and categorize their expenses, making financial management straightforward and intuitive.

## Getting Started

Clone the Repository:

```
git clone https://github.com/yourusername/flutter-expense-tracker.git
cd flutter-expense-tracker

```

### Install Dependencies:

```
flutter pub get
```

## Run the App:

```
flutter run

```


## Technologies Used


* Flutter: A UI toolkit for crafting natively compiled applications for mobile, web, and desktop from a single codebase.
* Dart: The programming language used by Flutter.
* Intl Package: For internationalization and localization, specifically for date formatting.
* UUID Package: To generate unique IDs for each expense.



## Key Features

Expense Entry:

* Users can add new expenses by providing a title, amount, date, and category.
* Input validation ensures that users enter valid information.
* A date picker allows users to select the date of the expense.
* Categories include Food, Travel, Leisure, and Work, each represented with an appropriate icon.

Expense List:

* Displays a list of expenses in a scrollable view.
* Each expense shows the title, amount, category icon, and formatted date.
* Uses a ListView.builder for efficient rendering of large lists.

User Interface:

* Utilizes Flutter's Material Design components for a cohesive and modern look.
* Card widgets and padding create a clean and structured layout.
* The main screen includes an app bar with a button to add new expenses, opening a modal bottom sheet.


  
