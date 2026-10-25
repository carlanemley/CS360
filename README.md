# CS 360: Mobile Architecture and Programming
## Inventory App – Project Three

### Project Overview

For my CS 360 project, I developed an Inventory App using Android Studio, Java, XML, and SQLite. The goal was to create a mobile application that allows users to organize and manage inventory without relying on handwritten records or manually updating spreadsheets.

The application includes user registration and login, inventory management, and optional SMS notifications when an item's quantity reaches zero. I also implemented a CSV import feature that allows users to upload multiple inventory items from an existing spreadsheet instead of entering each item individually.

### User Interface Design

I designed the application around three main screens:

- **Login Screen:** Allows users to create an account and sign in.
- **Inventory Screen:** Displays saved inventory items and allows users to add, update, delete, and import inventory records.
- **SMS Notification Screen:** Allows users to enter a phone number and enable optional inventory alerts.

My goal was to keep the interface simple and make frequently used features easy to access. I used clearly labeled buttons, straightforward navigation, and a table layout to display inventory information.

Although my interface is relatively basic, I focused on making the application functional and understandable for someone using it for the first time.

### Development Approach

I approached development by breaking the application into smaller features rather than attempting to build everything at once.

I started with the login and registration system, then connected the SQLite database to the inventory management features. Once those components were working, I implemented SMS notifications and eventually added CSV importing.

Working in smaller steps made troubleshooting easier because I could identify which part of the application was causing an issue. I also learned how important it is to understand the connections between Java, XML, and SQLite.

In future projects, I plan to continue developing and testing features individually before integrating them into the larger application.

### Testing and Troubleshooting

I tested my application using the Pixel 7 emulator in Android Studio.

My testing included:

- Creating user accounts and logging in.
- Adding inventory items manually.
- Updating item quantities.
- Deleting inventory records.
- Verifying that inventory information remained saved between sessions.
- Importing multiple inventory items using a CSV file.
- Testing the zero-stock SMS alert functionality.

I confirmed that the application detected when an item's quantity reached zero and submitted an SMS sending request. However, actual SMS delivery was not verified through the emulator.

Testing helped me identify errors, confirm that the database was functioning correctly, and ensure that new features did not interfere with existing functionality.

### Challenges and Innovation

One of the biggest things I learned throughout this project was how much work goes into developing even a relatively simple mobile application. Before this course, I didn't realize how many separate components needed to work together to create a functional app.

One challenge I identified was the process of entering inventory items individually. Although this met the original project requirements, I realized it would be inconvenient for someone managing hundreds of products.

To improve the application, I added a CSV import feature that allows users to select a spreadsheet file and import multiple inventory records at once. The feature also checks quantities and updates existing items with matching names instead of creating unnecessary duplicates.

This improvement required me to expand the database functionality and modify the inventory screen without disrupting the features I had already completed.

### My Most Successful Component

I am particularly proud of the CSV import feature because it was something I decided to implement after thinking about how someone would actually use the application.

Rather than focusing only on completing the assignment requirements, I wanted to address a limitation that could make the app frustrating to use.

Implementing this feature helped me strengthen my understanding of file handling, data validation, SQLite operations, and connecting new functionality to an existing interface.

Seeing the feature work successfully was one of the most rewarding parts of the project.

### Final Reflection

Completing this project changed how I view mobile application development. I knew programming required technical knowledge, but I underestimated the planning, testing, and troubleshooting involved in building even a basic application.

I can only imagine the amount of work and collaboration required to develop more complex applications with millions of users.

I do not currently plan to publish my Inventory App on the Google Play Store because I recognize that it is still a beginner-level project and that more polished applications already exist with similar functionality.

However, I consider this project a valuable learning experience and an example of my progress as a computer science student.

Moving forward, I would like to improve my user interface design skills and continue applying what I have learned about databases, application development, testing, and troubleshooting to future projects.

### Technologies Used

- Java
- XML
- SQLite
- Android Studio
- Android SDK
- Android Emulator (Pixel 7, API 34)

### Project Files

The completed Android Studio project is included in the repository as:

`CS360_InventoryApp_ProjectThree.zip`

The ZIP contains the Java source code, XML layouts, database implementation, and other Android Studio project files needed to review the application.
