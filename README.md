Empowering the Nation – Training App
Overview
This project is an Android application developed in Kotlin using Android Studio. It was designed for Empowering the Nation, an SME that provides skills training for domestic workers and gardeners. The app helps advertise the business, showcase available training courses, allow customers to select multiple courses, and automatically calculate discounts based on the number of courses chosen. Users can also request a quote directly through the app.
The app is built with a user-centered design process, ensuring simplicity, accessibility, and a professional look that reflects the company’s mission of empowering the community.
Features
Welcome Screen
Displays the business logo and a "Get Started" button to enter the app.
Courses Screen
Lists all available training courses (six-month and six-week programs).
Each course is displayed in a card with course name, description, price, and an "Add Course" button.
Supports selection of multiple courses.
Quote Screen
Shows selected courses, applicable discounts, and total price.
Discounts are calculated as follows:
1 course: No discount
2 courses: 5% discount
3 courses: 10% discount
More than 3 courses: 15% discount
Users can submit a quote request.
Technologies Used
Kotlin for application logic.
XML with ConstraintLayout, CardView, and ScrollView for modern, responsive UI design.
Android Studio for development and testing.
Project Structure
MainActivity.kt – Handles the welcome screen.
CoursesActivity.kt – Displays available courses and allows selection.
QuoteActivity.kt – Shows discounts, total fees, and submits a quote request.
res/layout/
activity_main.xml – Welcome screen layout.
activity_courses.xml – Courses listing layout with CardViews.
activity_quote.xml – Quote display layout.
res/drawable/ – Contains logo and icons.
res/values/ – Colors, themes, and styles for consistent branding.
Installation
Clone the repository or download the source code.
Open the project in Android Studio.
Sync Gradle dependencies.
Run the app on an emulator or physical Android device.
Future Improvements
Implement a bottom navigation bar for seamless movement between screens.
Add user authentication (login/register).
Enable payment gateway integration for course enrollment.
Build a web companion app for the same functionality.
Acknowledgment
This project was developed as part of a milestone assignment to demonstrate the use of user-centered design in mobile application development for an SME.
